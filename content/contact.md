---
title: Contact
sections:
- type: section_contact
  template: section_contact
  section_id: contact
  title: Contact
  content: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam a metus
    quis lorem malesuada luctus. Cras lacinia, eros at dapibus molestie, risus tortor
    pretium ligula.
  background: white
  form_id: contactForm
  form_fields:
  - type: form_field
    template: form_field
    input_type: text
    name: name
    label: Name
    is_required: true
    default_value: ''
    options: []
  - type: form_field
    template: form_field
    input_type: email
    name: email
    label: Email
    is_required: true
    default_value: ''
    options: []
  - type: form_field
    template: form_field
    input_type: select
    name: subject
    label: Subject
    default_value: Please select
    options:
    - Error on the site
    - Sponsorship
    - Other
    is_required: false
  - type: form_field
    template: form_field
    input_type: textarea
    name: message
    label: Message
    default_value: ''
    options: []
    is_required: false
  - type: form_field
    template: form_field
    input_type: checkbox
    name: consent
    label: I understand that this form is storing my submitted information so I can
      be contacted.
    is_required: true
    default_value: ''
    options: []
  submit_label: Send Message
  subtitle: ''
  form_action: ''
  hide_labels: false
seo:
  type: stackbit_page_meta
  template: stackbit_page_meta
  title: Contact
  description: This is the contact page
  extra:
  - name: og:type
    value: website
    keyName: property
    relativeUrl: false
  - name: og:title
    value: Contact
    keyName: property
    relativeUrl: false
  - name: og:description
    value: This is the contact page
    keyName: property
    relativeUrl: false
  - name: twitter:card
    value: summary_large_image
    keyName: ''
    relativeUrl: false
  - name: twitter:title
    value: Contact
    keyName: ''
    relativeUrl: false
  - name: twitter:description
    value: This is the contact page
    keyName: ''
    relativeUrl: false
  robots: []
layout: landing

---
