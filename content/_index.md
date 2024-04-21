---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
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
        #exclude_featured: true
    design:
      columns: "2"
      view: citation
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: "*"
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: "1"
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: "Accomplish&shy;ments"
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      items:
        - certificate_url: https://www.coursera.org/account/accomplishments/certificate/5QF8UWJWL8MM
          date_end: ""
          date_start: "2020-06-15"
          description: ""
          icon: coursera
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Deep Learning Specialization
          url: ""
        - certificate_url: https://www.coursera.org/account/accomplishments/specialization/certificate/MEH953AKU9L6
          date_end: ""
          date_start: "2020-08-02"
          description: ""
          icon: coursera
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Reinforcement Learning Specialization
          url: ""
        - certificate_url: https://www.coursera.org/account/accomplishments/verify/QXAQHCHUT7L8
          date_end: ""
          date_start: "2020-07-05"
          description: ""
          icon: coursera
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Game Theory
          url: ""
        - certificate_url: https://www.credly.com/badges/159db5d0-81b1-4597-bdff-056b43865b59
          date_end: ""
          date_start: "2020-06-16"
          description: ""
          icon: coursera
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Data Science Orientation
          url: ""
    design:
      columns: "2"
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      email: seyyidahmed.lahmer@unipd.it
    design:
      columns: "2"
---
