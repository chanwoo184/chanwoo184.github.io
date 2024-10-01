---
widget: slider
weight: 5
active: true
headless: true

design:
    slide_height: '300px'
    slide_width: '100px'
    is_fullscreen: false
  # Automatically transition through slides?
    loop: true
  # Duration of transition between slides (in ms)
    interval: 5000

content:
    slides:

    - title: <span style="font-size:90%">Welcome!</span>
      content: <span style="font-size:90%">**welcome to my web page**<span style="font-size:90%">
      align: center

      background:
        position: center
        color: '#333'
        brightness: 0.4
        media: welcome.jpg
        fit: cover

    - title: <span style="font-size:90%">Devolp</span>
      content: <span style="font-size:90%">C++로 즐기는 개발 과정</span>
      align: center
      background:
        position: center
        color: '#333'
        brightness: 0.4
        media: code.jpg
        fit: cover
    
    - title: <span style="font-size:90%">Contact</span>
      content: create with me?
      align: right
      background: 
        position: center
        color: '#333'
        brightness: 0.4
        media: contact.jpg
        fit: cover
      link:
        icon: phone
        icon_pack: fas
        text: <span style="font-size:60%">Contact</span>
        url: contact/
---