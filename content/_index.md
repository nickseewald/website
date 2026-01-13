---
title: Nick Seewald, PhD
type: landing

sections:
  - block: about.biography
    id: bio
    content:
    #   title: Hi, I'm Nick.
      username: admin
  
  - block: slider
    content:
      slides:
        - title: New Webinar
          content: |
            Watch my webinar on [**Target Trial Emulation for Evaluating Mental Health Policy**](talks/alacrity-methods-2025/) for the [Johns Hopkins ALACRITY Center for Health & Longevity in Mental Illness](https://publichealth.jhu.edu/alacrity-center-for-health-and-longevity-in-mental-illness)
          align: center
          background:
            image:
              filename: alacrityBackground.png
              fit: contain
              filters:
                brightness: 0.5
                blur: '1rem'
            position: right
            color: '#8D99AE'
          link:
            icon: youtube
            icon_pack: fab
            text: Watch now!
            url: "https://www.youtube.com/watch?v=DAXfp8X9ba8"
        - title: New Webinar
          content: |
            Watch the first hour of my seminar **SMART Designs for Developing Adaptive Interventions** with [Statistical Horizons](https://www.statisticalhorizons.com).
          align: center
          background:
            image:
              filename: statHorizonsBackground.png
              fit: contain
              filters:
                brightness: 0.5
                blur: '1rem'
          link:
            icon: youtube
            icon_pack: fab
            text: Watch now!
            url: https://youtu.be/UFABO4oqNGs?si=KGvn7mh4myZkZrHK
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '500px'
      # Make the slides full screen within the browser window?
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 5000

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
      columns: '1'

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
        exclude_future: false
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
      columns: '1'


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
      columns: '1'
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
        street: 3600 Civic Center Drive, Room 3W-103
        city: Philadelphia
        region: PA
        postcode: "19104"
        country: United States
        country_code: 1
      coordinates:
        latitude: "39.94611862746245" 
        longitude: "-75.19669922542555"
    design:
      columns: "1"
---