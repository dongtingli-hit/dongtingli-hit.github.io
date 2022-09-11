---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: dalton.dtli@gmail.com; dtli@hit.edu.cn
  phone: +86 13682328601
  address:
    street: West Dazhi Street
    city: Harbin
    postcode: '150001'
    country: P.R.China
    country_code: CHN
  coordinates:
    latitude: '45.75'
    longitude: '126.64'
  directions: Room 606, Main building


design:
  columns: '2'
---
