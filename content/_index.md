---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin


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
        - title: Member of Tensor Modeling and Computation Team
          company: University of Electronic Science and Technology of China
          company_url: 'https://www.uestc.edu.cn/'
          company_logo: uestc_logo
          location: Chengdu
          date_start: '2022-07-01'
          date_end: ''
          description: Modeling tensors and designing tensor recovery algorithms.
    design:
      columns: '2'
  

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
      
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false



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



  - block: collection
    content:
      title: Recent Publications
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



  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'



  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
      
      # Contact (add or remove contact options as necessary)
      email: xiejinyu475@outlook.com
      address:
        street: 2006, Xiyuan Avenue, West High-tech Zone
        city: Chengdu
        region: Sichuan Province
        postcode: '611731'
        country: China
        country_code: CHI
      
    design:
      columns: '2'
---
