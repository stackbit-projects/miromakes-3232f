---
title: contact
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: >-
      Hi there! Please
      fill the contact form below to get in touch.
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: text
        name: subject
        label: Subject
        default_value: Topic
        options:
          - Error on the site
          - Sponsorship
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
    submit_label: Send Message
layout: advanced
---
