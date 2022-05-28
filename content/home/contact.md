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
  email: 1032216510@pfur.ru
  address:
    street: Miklukho-Maclay
    city: Moscow
    country: Russian Federation
    country_code: RF
 
  contact_links:
    - icon: book
      icon_pack: fas
      name: eLibrary
      link:  'https://elibrary.ru/'
    - icon: graduation-cap
      icon_pack: fas
      name: Google Scholar
      link: 'https://scholar.google.com/'
    - icon: orcid
      icon_pack: fab
      name: ORCID
      link: 'https://orcid.org/'
    - icon: mendeley
      icon_pack: fab
      name: Mendeley
      link: 'https://www.mendeley.com/'
    - icon: researchgate
      icon_pack: fab
      name: ResearchGate
      link: 'https://www.researchgate.net/'
    - icon: a
      icon_pack: fas
      name: academia.edu
      link: 'https://www.academia.edu/'
    - icon: book-open
      icon_pack: fas
      name: arXiv
      link: 'https://arxiv.org/'
    - icon: github
      icon_pack: fab
      name: github
      link: 'https://github.com/'

design:
  columns: '2'
---
