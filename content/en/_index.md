---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Tode Lab
      image:
        filename: jpn48.png
      text: |
        <br>
        
        Department of Core Informatics<br>Graduate School of Informatics<br>Osaka Metropolitan University<br>Japan
  
  #- block: collection
  #  content:
  #    title: Latest News
  #    subtitle:
  #    text:
  #    count: 5
  #    filters:
  #      author: ''
  #      category: ''
  #      exclude_featured: false
  #      publication_type: ''
  #      tag: ''
  #    offset: 0
  #    order: desc
  #    page_type: post
  #  design:
  #    view: card
  #    columns: '1'
  
  #- block: markdown
  #  content:
  #    title:
  #    subtitle: ''
  #    text:
  #  design:
  #    columns: '1'
  #    background:
  #      image: 
  #        filename: coders.jpg
  #        filters:
  #          brightness: 1
  #        parallax: false
  #        position: center
  #        size: cover
  #        text_color_light: true
  #    spacing:
  #      padding: ['20px', '0', '20px', '0']
  #    css_class: fullscreen

  - block: slider
    content:
      slides:
      - title: 👋 Welcome to Tode Lab
        content: Take a look at what we're working on...
        align: center
        background:
          image:
            filename: fiber.jpg
            filters:
              brightness: 0.3
          position: right
          color: '#666'
        link:
          icon: search
          icon_pack: fas
          text: About Us
          url: ./about/
      - title: Projects
        content: Share your knowledge with our group and explore exciting new topics together!
        align: left
        background:
          image:
            filename: server.jpg
            filters:
              brightness: 0.3
          position: center
          color: '#555'
        link:
          icon: search
          icon_pack: fas
          text: Check our projects
          url: ./projects/
      - title: Achievements
        content: We have amassed numerous achievements since 2008
        align: right
        background:
          image:
            filename: work.jpg
            filters:
              brightness: 0.3
          position: center
          color: '#333'
        link:
          icon: search
          icon_pack: fas
          text: Check our achievements
          url: ./achievements/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '20rem'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 4000
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---