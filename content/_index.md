---
# Leave the homepage title empty to use the site title
title:
date: 2023-10-24
type: landing

sections:
  - block: hero
    content:
       
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        <font size="3"> A "sepal" shields and supports flower petals, often green, guarding the bud before blooming.  "Sepal" likens this protection to privacy and security.</font>
  
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
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
       
    design:
      columns: '1'
---