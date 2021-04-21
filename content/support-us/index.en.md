+++
fragment = "content"
#disabled = true
date = "2021-04-08"
weight = 100
#background = ""
title = "Support Nothelfer365"
+++

Als Verein sind wir auf die Unterstützung unserer Mitglieder angewiesen.
Wenn du [den Zweck und die Mission des Vereins](/ueber-uns) fördern möchtest, stehen dir verschiedene Mitgliedschaften zur Verfügung.
Darüber hinaus kannst du als Instruktor bei uns die nötigen Zertifizierungen erwerben und selbst Kurse unterrichten.
Als Partner können Unternehmen, Organisationen und andere Vereine eine Zusammenarbeit mit uns aufnehmen und so besondere Konditionen bei unseren Kursen erhalten.

### Membership levels

- **Supporters** support us with a custom monthly donation.
- **Passive members** support us with at least 10 CHF per month.
- **Active members** support us with at least 50 CHF per month and gain voting rights at the assembly.
- **Instructors** support us by teaching our courses.
- **Partners** are organisations or enterprises supporting us with a custom monthly donation to gain access to custom discounts and courses.

### Become a member

<form id="fs-frm" name="department-contact-form" accept-charset="utf-8" action="https://formspree.io/f/xpzkwoak" method="post">
  <fieldset id="fs-frm-inputs">
    <label for="full-name">Name</label>
    <input type="text" name="name" id="full-name" placeholder="First Last" required="">
    <label for="email-address">Email</label>
    <input type="email" name="_replyto" id="email-address" placeholder="email@domain.tld" required="">
    <label for="tier">Membership</label>
    <select name="tier" id="tier" required="">
      <option value="Select" selected="" disabled="">Choose</option>
      <option value="goenner">Supporter</option>
      <option value="passivmitglied">Passive member</option>
      <option value="aktivmitglied">Active member</option>
      <option value="instruktor">Instructor</option>
      <option value="partner">Partner</option>
    </select>
    <label for="message">MEssage</label>
    <textarea rows="5" name="message" id="message"></textarea>
    <input type="hidden" name="_subject" id="email-subject" value="Membership request">
    <input type="hidden" name="lang" id="lang" value="en">
  </fieldset>
  <input type="submit" value="Become a member now">
</form><style>/* reset */
#fs-frm input,
#fs-frm select,
#fs-frm textarea,
#fs-frm fieldset,
#fs-frm optgroup,
#fs-frm label,
#fs-frm #card-element:disabled {
  font-family: inherit;
  font-size: 100%;
  color: inherit;
  border: none;
  border-radius: 0;
  display: block;
  width: 100%;
  padding: 0;
  margin: 0;
  -webkit-appearance: none;
  -moz-appearance: none;
}
#fs-frm label,
#fs-frm legend,
#fs-frm ::placeholder {
  font-size: .825rem;
  margin-bottom: .5rem;
  padding-top: .2rem;
  display: flex;
  align-items: baseline;
}

/* border, padding, margin, width */
#fs-frm input,
#fs-frm select,
#fs-frm textarea,
#fs-frm #card-element {
  border: 1px solid rgba(0,0,0,0.2);
  background-color: rgba(255,255,255,0.9);
  padding: .75em 1rem;
  margin-bottom: 1.5rem;
}
#fs-frm input:focus,
#fs-frm select:focus,
#fs-frm textarea:focus {
  background-color: white;
  outline-style: solid;
  outline-width: thin;
  outline-color: gray;
  outline-offset: -1px;
}
#fs-frm [type="text"],
#fs-frm [type="email"] {
  width: 100%;
}
#fs-frm [type="button"],
#fs-frm [type="submit"],
#fs-frm [type="reset"] {
  width: auto;
  cursor: pointer;
  -webkit-appearance: button;
  -moz-appearance: button;
  appearance: button;
}
#fs-frm [type="button"]:focus,
#fs-frm [type="submit"]:focus,
#fs-frm [type="reset"]:focus {
  outline: none;
}
#fs-frm [type="submit"],
#fs-frm [type="reset"] {
  margin-bottom: 0;
}
#fs-frm select {
  text-transform: none;
}

#fs-frm [type="checkbox"] {
  -webkit-appearance: checkbox;
  -moz-appearance: checkbox;
  appearance: checkbox;
  display: inline-block;
  width: auto;
  margin: 0 .5em 0 0 !important;
}

#fs-frm [type="radio"] {
  -webkit-appearance: radio;
  -moz-appearance: radio;
  appearance: radio;
}

/* address, locale */
#fs-frm fieldset.locale input[name="city"],
#fs-frm fieldset.locale select[name="state"],
#fs-frm fieldset.locale input[name="postal-code"] {
  display: inline;
}
#fs-frm fieldset.locale input[name="city"] {
  width: 52%;
}
#fs-frm fieldset.locale select[name="state"],
#fs-frm fieldset.locale input[name="postal-code"] {
  width: 20%;
}
#fs-frm fieldset.locale input[name="city"],
#fs-frm fieldset.locale select[name="state"] {
  margin-right: 3%;
}
</style>