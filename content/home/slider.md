---
sections:

  design:
    slide_height: '350px'
    slide_width: '100px'
    is_fullscreen: true
    # Automatically transition through slides?
    loop: true
    # Duration of transition between slides (in ms)
    interval: 3000

  - block: slider
    content:
      slides:

      - title: <span style="font-size:90%">Welcome!</span>
        content: <span style="font-size:90%">**welcome to my web page**</span>
        align: center
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:90%">Devolp</span>
        content: <span style="font-size:90%">C++로 즐기는 개발 과정</span>
        align: center
        background:
          image:
            filename: code.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
---
