---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: kolkata.jpg
          filters:
            brightness: 0.2
          size: cover
          position: bottom
          parallax: true
  - block: collection
    id: papers
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: citation
  - block: markdown
    id: contact
    content:
      title: 'Contact'
      subtitle: ''
      text: |-
        <p style="text-align: center;">Delft University of Technology</br>  
        Room 6.E.420, Van Mourik Broekmanweg 6,</br> 2628 XE Delft, The Netherlands     
        </p>
    design:
      columns: '1'
---
