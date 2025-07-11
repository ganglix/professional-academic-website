---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about # id is the address linking to menu
    content:
      title: ''
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin



#   - block: portfolio
#     content:
#       title: Teaching courses
#         folders: 
#           - course
#     design:
#       # Choose how many columns the section has. Valid values: '1' or '2'.
#       columns: '2'


#   - block: skills
#     content:
#       title: Skills
#       text: ''
#       # Choose a user to display skills from (a folder name within `content/authors/`)
#       username: admin
#     design:
#       columns: '1'
#   - block: accomplishments
#     content:
#       # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
#       title: 'Accomplish&shy;ments'
#       subtitle:
#       # Date format: https://docs.hugoblox.com/customization/#date-format
#       date_format: Jan 2006
#       # Accomplishments.
#       #   Add/remove as many `item` blocks below as you like.
#       #   `title`, `organization`, and `date_start` are the required parameters.
#       #   Leave other parameters empty if not required.
#       #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
#       items:
#         - certificate_url: https://www.coursera.org
#           date_end: ''
#           date_start: '2021-01-25'
#           description: ''
#           icon: coursera
#           organization: Coursera
#           organization_url: https://www.coursera.org
#           title: Neural Networks and Deep Learning
#           url: ''
#         - certificate_url: https://www.edx.org
#           date_end: ''
#           date_start: '2021-01-01'
#           description: Formulated informed blockchain models, hypotheses, and use cases.
#           icon: edx
#           organization: edX
#           organization_url: https://www.edx.org
#           title: Blockchain Fundamentals
#           url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
#         - certificate_url: https://www.datacamp.com
#           date_end: '2020-12-21'
#           date_start: '2020-07-01'
#           description: ''
#           icon: datacamp
#           organization: DataCamp
#           organization_url: https://www.datacamp.com
#           title: 'Object-Oriented Programming in R'
#           url: ''
#     design:
#       columns: '2'
#   - block: collection
#     id: posts
#     content:
#       title: Recent Posts
#       subtitle: ''
#       text: ''
#       # Choose how many pages you would like to display (0 = all pages)
#       count: 5
#       # Filter on criteria
#       filters:
#         folders:
#           - post
#         author: ""
#         category: ""
#         tag: ""
#         exclude_featured: false
#         exclude_future: false
#         exclude_past: false
#         publication_type: ""
#       # Choose how many pages you would like to offset by
#       offset: 0
#       # Page order: descending (desc) or ascending (asc) date.
#       order: desc
#     design:
#       # Choose a layout view
#       view: compact
#       columns: '2'

  - block: portfolio
    id: portfolio
    content:
      title: Portfolio
      filters:
        folders:
          - portfolio
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Bridge
          tag: Bridge
        - name: Mining
          tag: Mining
        - name: Concrete
          tag: Concrete
        - name: Corrosion
          tag: Corrosion
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: compact
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
#   - block: markdown
#     content:
#       title: Gallery
#       subtitle: ''
#       text: |-
#         {{< gallery album="demo" >}}
#     design:
#       columns: '1'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: portfolio
    content:
      title: Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [searching publications](./publication/), filtering using the tabs below, or exploring [popular topics](./tags/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        # exclude_featured: true  # not even applicable for portfolio.
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Corrosion
          tag: Corrosion
        - name: Concrete
          tag: Concrete
        - name: Rebar
          tag: Rebar
        - name: Crack
          tag: Crack
        - name: Numerical Simulation
          tag: Numerical Simulation
        - name: Potentiodynamic scan
          tag: Potentiodynamic scan
        - name: Transport
          tag: Transport
        - name: Moisture
          tag: Moisture
        - name: Chloride
          tag: Chloride
        - name: Carbonation
          tag: Carbonation
        - name: Life cycle
          tag: Life cycle
        - name: Case study
          tag: Case study
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: compact
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
      
  - block: collection
    id: teaching
    content:
      title: Teaching
      filters:
        folders:
          - course
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: list

  - block: portfolio
    id: tools
    content:
      title: Tools
      filters:
        folders:
          - tools
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: card
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

#   - block: tag_cloud
#     content:
#       title: Popular Topics
#     design:
#       columns: '2'


  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
              I provide consulting services in corrosion science, material performance evaluation, and infrastructure durability—particularly for concrete structures, metallic structures in potash and mining environments.

              Use the form below to reach out for service inquiries, collaboration opportunities, or a free initial consultation. I typically respond within 1–2 business days.


      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true
    design:
      columns: '2'
---
