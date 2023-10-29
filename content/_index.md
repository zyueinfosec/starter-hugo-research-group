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
        
        <font size="3"> The term "sepal" typically refers to one of the leaf-like structures that protect and support the petals of a flower. Sepals are typically green and enclose and protect the flower bud before it blooms. In the context of security labs, **"SePAL"** is a creative and metaphorical name that draws an analogy between the protective function of sepals in flowers and the protective function of our security lab in the realm of information privacy and security.</font>
  
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