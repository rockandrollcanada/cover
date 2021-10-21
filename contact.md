---
layout: page
forms:
  - to: joost@vdschee.nl
    subject: New submission!
    redirect: /jekyllconf2019_live
    form_engine: cloudcannon
    placeholders: false
    fields:
      - name: name
        input_type: text
        placeholder: Name
        required: true
      - name: email
        input_type: email
        placeholder: Email address
        required: true
      - name: message
        input_type: textarea
        placeholder: Message
        required: false
      - name: terms
        input_type: checkbox
        placeholder: I accept the terms and conditions
        required: true
      - name: submit
        input_type: submit
        placeholder: Submit form
        required: true
---

# Contact

Lorem ipsum… [this is a link](https://www.google.com){: target="_blank"}

*this is italic*