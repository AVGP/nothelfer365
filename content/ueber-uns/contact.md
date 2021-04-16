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
button_text = "Abschicken" # defaults to theme default
#netlify = false

# Optional google captcha
# Won't be used if netlify is enabled
#[recaptcha]
#  sitekey = ""

[message]
  success = "Danke für deine Nachricht, wir werden uns bald melden." # defaults to theme default
  error = "Hoppla, das hat leider nicht geklappt! Versuch es noch einmal" # defaults to theme default

# Only defined fields are shown in contact form
[fields.name]
  text = "Dein Name *"
  error = "Bitte gib deinen Namen an, damit wir wissen, wer du bist" # defaults to theme default

[fields.email]
  text = "Deine Email-Adresse *"
  error = "Bitte gib deine Email-Adresse ein, damit wir dir antworten können" # defaults to theme default

#[fields.phone]
#  text = "Your Phone *"
#  error = "Please enter your phone number" # defaults to theme default

[fields.message]
  text = "Deine Nachricht *"
  error = "Was möchtest du uns sagen?" # defaults to theme default

# Optional hidden form fields
# Fields "page" and "site" will be autofilled
#[[fields.hidden]]
#  name = "page"

#[[fields.hidden]]
#  name = "someID"
#  value = "example.com"
+++
