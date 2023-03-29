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
          company_logo: org-gc
          location: Geneva
          date_start: '2021-01-01'
          date_end: ''
          description: Development and usage of the tool \href{https://gitlab.com/plcverif-oss}{PLCverif} to automatically formally verify PLC code.
        - title: Model Validation Specialist
          company: Deutsche Bank
          company_url: ''
          company_logo: org-x
          location: Frankfurt
          date_start: '2016-01-01'
          date_end: '2020-12-31'
          description: Validation of Machine Learning models to estimate credit score by performing different analyses, such as assumptions validation, sensitivity, robustness, and back-testing.
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
        - title: Ph.D. Computer Science
          company: TU Wien
          company_url: ''
          company_logo: org-gc
          location: Vienna, Austria
          date_start: '2022-09-01'
          date_end: ''
          description: xxx
        - title: M.Sc. Artificial Intelligence Research
          company: Menendez Pelayo University
          company_url: ''
          company_logo: org-x
          location: California
          date_start: '2019-09-01'
          date_end: '2021-19-01'
          description: xxx
    design:
      columns: '2'
  - block: collection
    content:
      title: Publications
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
        street: Treitlstrasse 3
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
