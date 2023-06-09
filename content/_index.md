---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Formal Verification Engineer
          company: CERN
          company_url: ''
          company_logo: cern
          location: Geneva
          date_start: '2020-03-01'
          date_end: '2022-08-31'
          description: Development and usage of the tool PLCverif to automatically formally verify PLC code.
        - title: Model Validation Specialist
          company: Deutsche Bank
          company_url: ''
          company_logo: deutsche_bank
          location: Frankfurt
          date_start: '2017-11-01'
          date_end: '2019-12-31'
          description: Validation of Machine Learning models to estimate credit score by performing different analyses, such as assumptions validation, sensitivity, robustness, and back-testing.
        - title: Quantitative consultant
          company: Management Solutions
          company_url: ''
          company_logo: management_solutions
          location: Madrid and London
          date_start: '2015-09-01'
          date_end: '2017-09-30'
          description: Design and development of tools to automate processes, as well as validation of Machine Learning models.
    design:
      columns: '2'
  - block: experience
    content:
      title: Education
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Ph.D. Logic in Computer Science
          company: TU Wien
          company_url: ''
          company_logo: tu-wien
          location: Vienna
          date_start: '2022-09-01'
          date_end: ''
          description: 
        - title: M.Sc. Artificial Intelligence Research
          company: Menendez Pelayo University
          company_url: ''
          company_logo: uimp
          location: Online
          date_start: '2019-09-01'
          date_end: '2021-09-01'
          description: 
        - title: B.Sc. Mathematics
          company: National University of Distance Education
          company_url: ''
          company_logo: uned
          location: Distance learning
          date_start: '2016-09-01'
          date_end: ''
          description: 
        - title: M.Sc. Business Consulting
          company: ICADE Business School
          company_url: ''
          company_logo: icade
          location: Madrid
          date_start: '2015-09-01'
          date_end: '2017-08-31'
          description: 
        - title: B.Sc. Industrial Electronics and Automation Engineering
          company: Valladolid University
          company_url: ''
          company_logo: uva
          location: Valladolid
          date_start: '2011-09-01'
          date_end: '2015-08-31'
          description: 
    design:
      columns: '2'
  - block: collection
    id: news
    content:
      title: News
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - news
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
  - block: collection
    id: publications
    content:
      title: Publications
      id: publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: ignacio.lopez [at] tuwien.ac.at
      address:
        street: 3 Treitlstrasse
        city: Vienna
        region: 
        postcode: '1040'
        country: Austria
        country_code: AT
      # Automatically link email and phone or display as text?
      autolink: false
    design:
      columns: '2'
---
