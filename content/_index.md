---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "3rem"

sections:
  - block: resume-biography-custom
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: files/cv_souza.pdf
    design:
      css_class: light
      background:
        color: light
        image:
          # Add your image background to `assets/media/`.
          filename: 
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: collection
    content:
      title: Recent Publications
      # Choose how many pages you would like to display (0 = all pages)
      count: 3
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: work-in-progress
    content:
      title: Work in Progress
      # Choose how many pages you would like to display (0 = all pages)
      count: 3
      text: ""
      filters:
        folders:
          - work-in-progress
        exclude_featured: false
    design:
      view: citation       
  - block: markdown
    id: contact
    content:
      title: Contact
      text: |-
        Please reach out in case you have any questions or want to talk about research.
        
        #### Email
        danielfernando.desouza [at] polimi [dot] it
        
        
        #### Address
        Department of Management, Economics and Industrial Engineering\
        Polytechnic University of Milan\
        Via Lambruschini, 4b, 20156\
        Milan, Italy
      filters:
        folders:
          - contact
        exclude_featured: false
    design:
      view: citation
---