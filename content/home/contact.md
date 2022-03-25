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
  phone: 06 49 92 00 53
  address:
    street: Campus Savoie Technolac
    city: Le Bourget-du-lac
    region: Savoie
    postcode: '73376'
    country: France
    country_code: FR
  coordinates:
    latitude: '45.65788'
    longitude: '5.86800'
  directions: Building 8A, Second floor, Room 206

design:
  columns: '2'
---
