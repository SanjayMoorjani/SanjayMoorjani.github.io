---
# Leave the homepage title empty to use the site title
title: 
date: 2022-10-24
type: landing
sections:
  - block: about.biography
    id: about
    content:
      title: 
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: publications
    content:
      title: Research
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
      view: card
  - block: accomplishments
    id: teaching
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Teaching'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - date_end: ''
          date_start: ''
          description: Fall 2023
          organization: Boston College
          title: ECON 2202 Macroeconomic Theory (Undergraduate)
          url: ''
        - date_end: ''
          date_start: ''
          description: Summer 2023
          organization: Boston College
          title: INTL 3372 International Finance (Undergraduate)
          url: ''
    design:
      columns: '2'
---
