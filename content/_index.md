---
title: Nick Seewald, PhD
type: landing

sections:
  - block: about.biography
    id: bio
    content:
    #   title: Hi, I'm Nick.
      username: admin

  - block: collection
    id: home_pubs
    class: section_font
    content:
      title: Featured Publications
      subtitle: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 2
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - publication
        author: ""
        category: ""
        tag: ""
        publication_type: ""
        featured_only: true
        exclude_featured: false
        exclude_future: true
        exclude_past: false
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
      offset: 0
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
    design:
      # Choose a listing view
      view: compact
      # Choose single or dual column layout
      columns: '2'

  - block: collection
    id: home_talks
    content:
      title: Recent & Upcoming Talks
      subtitle: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 2
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - event
        author: ""
        category: ""
        tag: ""
        publication_type: ""
        featured_only: false
        exclude_featured: false
        exclude_future: true
        exclude_past: false
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
      offset: 0
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
    design:
      # Choose a listing view
      view: compact
      # Choose single or dual column layout
      columns: '2'


  - block: portfolio
    id: home_software
    content:
      title: Software
      subtitle: 
      filters:
        # Folders to display content from
        folders:
          - project
        # Only show content with these tags
        tags: [software]
        # Exclude content with these tags
        exclude_tags: []
        # Which Hugo page kinds to show (https://gohugo.io/templates/section-templates/#page-kinds)
        kinds:
          - page
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      # Choose a listing view
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

  - block: contact
    id: home_contact
    content:
      title: Contact
      text: ''
      autolink: false
      form:
        provider: netlify
        netlify:
          captcha: true
      email: 'See my CV or use the form.'
      address:
        street: 624 Blockley Hall, 423 Guardian Drive
        city: Philadelphia
        region: PA
        postcode: "19104"
        country: United States
        country_code: 1
      coordinates:
        latitude: "39.94862488310947"
        longitude: "-75.19739135929261"
    design:
      columns: "2"
---