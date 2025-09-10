---
# Leave the homepage title empty to use the site title
title:
date: 2025-09-09
type: landing


  - block: slider
    content:
      slides:
      - title: QuMAP - Quantum Materials and Astroparticle Physics
        content: 'See what we are working on...'
        align: center
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'

      - title: Dark Matter Detection
        content: 'INSERT INFO HERE'
        align: left
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
        link:
          icon: search
          icon_pack: fas
          text: Find out more
          url: '#dmd'

        
      - title: New Detection Mechanism
        content: 'INSERT INFO HERE'
        align: left
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
        link:
          icon: search
          icon_pack: fas
          text: Find out more
          url: '#newdetection'

        
      - title: Superfluids
        content: 'INSERT INFO HERE'
        align: right
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: search
          icon_pack: fas
          text: Find out more
          url: '#superfluids'
        
      - title: AI Designed Molecules
        content: 'INSERT INFO HERE'
        align: left
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
        link:
          icon: search
          icon_pack: fas
          text: Find out more
          url: '#AI'

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000

  - block: hero
    id: dmd
    content:
      image:
        filename: LogoQMAPBlank.png
      title: |
        Dark Matter Detection
      text: |
        <br>
        DETAILS
    
  - block: hero
    id: newdetection
    content:
      image:
        filename: LogoQMAPBlank.png
      title: |
        New Detection Mechanism
      text: |
        <br>
        DETAILS
    
  - block: hero
    id: superfluids
    content:
      image:
        filename: LogoQMAPBlank.png
      title: |
        Superfluids
      text: |
        <br>
        DETAILS

  - block: hero
    id: AI
    content:
      image:
        filename: LogoQMAPBlank.png
      title: |
        AI Molecules
      text: |
        <br>
        DETAILS
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
