+++
fragment = "contact"
#disabled = true
date = "2017-09-10"
weight = 110
background = "secondary"
form_name = "defaultContact"

#title = "Contact fragment"
#subtitle  = "*not working on demo page*"
#title_align = "left" # Default is center, can be left, right or center

# PostURL can be used with backends such as formspree, or mailout from caddy
post_url = "https://formspree.io/f/xzbyzdbw"
#email = "mail@example.com"
button_text = "Send" # defaults to theme default
#netlify = false

# Optional google captcha
# Won't be used if netlify is enabled
#[recaptcha]
#  sitekey = ""

[message]
  success = "Thank you for sending us a message, we will get back to you soon!" # defaults to theme default
  error = "Whoops, that didn't work. Please try again" # defaults to theme default

# Only defined fields are shown in contact form
[fields.name]
  text = "Your Name *"
  error = "Please tell us who you are" # defaults to theme default

[fields.email]
  text = "Your Email *"
  error = "Please tell us how we can get in touch with you via email" # defaults to theme default

#[fields.phone]
#  text = "Your Phone *"
#  error = "Please enter your phone number" # defaults to theme default

[fields.message]
  text = "Your message *"
  error = "What would you like to tell us?" # defaults to theme default

# Optional hidden form fields
# Fields "page" and "site" will be autofilled
#[[fields.hidden]]
#  name = "page"

#[[fields.hidden]]
#  name = "someID"
#  value = "example.com"
+++
