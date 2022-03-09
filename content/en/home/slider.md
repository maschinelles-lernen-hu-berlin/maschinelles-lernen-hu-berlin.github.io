---
widget: slider
weight: 100
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: '300px'
  is_fullscreen: false
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
  - title: Eidetic Representations of Natural Language
    content: In this 6-year project, we are looking to advance the state of the art in neural language modeling (BERT, GPT-3).
    align: right
    color: '#123'
    background:
      position: left
      color: '#123'
      brightness: 0.9
      media: logo_emmy_noether_gross.jpg
  - title: Lunch & Learn ☕️
    content: 'Share your knowledge with the group and explore exciting new topics together!'
    align: left
    background:
      position: center
      color: '#555'
      brightness: 0.7
      media: contact.jpg
  - title: World-Class Semiconductor Lab
    content: 'Just opened last month!'
    align: right
    background:
      position: center
      color: '#333'
      brightness: 0.5
      media: welcome.jpg
    link:
      icon: graduation-cap
      icon_pack: fas
      text: Join Us
      url: ../contact/
---
