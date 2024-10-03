---
# Page title
title: TODO APP project
date: '2023-10-10' # 원하는 날짜로 변경
# Page type - we want a landing page (such as a homepage)

# Your landing page sections - add as many different content blocks as you like
sections:
  - block: markdown
    id: section-1
    content:
      title: TODO APP project
      
      subtitle: .
      text: I am creating a todoapp using the website creation reference book https://wikidocs.net/book/7601.

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: todoapp.png
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['100px', '200px', '100px', '200px']
      #css_class: fullscreen
---