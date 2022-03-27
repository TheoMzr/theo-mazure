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
  email: theo.mazure@inrae.fr
  phone: (+33) 06 49 92 00 53
  address:
    street: Office 206, Building 8A, Campus Savoie Technolac, 73376
    city: Le Bourget-du-lac, France
  coordinates:
    latitude: '45.641785'
    longitude: '5.868029'

design:
  columns: '2'
---
