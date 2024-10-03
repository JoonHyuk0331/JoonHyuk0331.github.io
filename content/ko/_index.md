---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        JoonHyuk Kim
      image:
        filename: webmypic.jpg
      text: |
        <br>
        -짧은 소개-
        웹 프로그래밍에 관심있는 컴퓨터공학과 학생입니다. 
      cta:
        label: Download Résumé
        url: /uploads/joon_resume.pdf
        #icon_pack: fas
        #icon: download
      # Optionally, add an alternative CTA link


  - block: contact
    content:
      title: Contact
      text: |-
        <br> <span style="font-size:95%">I am living in 한빛관 of Chonbuk National University.</span> <br>
      email: joonlife0901@gmail.com
      address:
        street: 전북대학교 한빛관
        city: 전주시
        region: 전라북도
        postcode: '54896'
        country: 대한민국
        country_code: KO
      coordinates:
        latitude: '35.851123'
        longitude: '127.128695'
      directions: 
      contact_links:
        - icon: github
          icon_pack: fab
          name: go to github page
          link: https://github.com/JoonHyuk0331
          
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: true
    design:
      columns: '3'
  
  - block: slider
    content:
      slides:

      - title: <span class="text-overlay">coding</span>
        content: <span style="font-size:70%">study code</span>
        align: center
        background:
          image:
            filename: code1.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        #link:
        #  icon: user
        #  icon_pack: fas
        #  text: <span style="font-size:60%">Join Us</span>
        #  text-color: '#000'
        #  url: contact

      - title: <span style="font-size:70%">AI</span>
        content: <span style="font-size:70%">learning ai!<span style="font-size:70%">
        align: center
        background:
          image:
            filename: code2.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Cat</span>
        content: <span style="font-size:70%">Look at the cute cat</span>
        align: center
        background:
          image:
            filename: catimage.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '350px'
      slide_width: '100px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000

  - block: features
    id: features
    content:
      title: <span style="font-size:75%">Interests</span>
      text: I am currently studying the following fields of interest.<br><br><br><br>
      items:
        - name: Artificial Intelligence (AI)
          icon: code-branch
          icon_pack: fas
          description: <span style="font-size:90%">AI technologies such as machine learning, computer vision, and natural language processing.</span><br><br>
        - name: Web Crawling
          icon: globe
          icon_pack: fas
          description:  <span style="font-size:90%">Collecting and utilizing large amounts of data through web crawling.</span><br><br>
        - name: Mathematics
          icon: calculator
          icon_pack: fas
          description:  <span style="font-size:90%">Mathematical theories related to AI, such as linear algebra.</span><br><br>
        - name: Backend Development 
          icon: server
          icon_pack: fas
          description:  <span style="font-size:90%">Server construction and database utilization.</span><br><br>
        - name: Frontend Development 
          icon: laptop
          icon_pack: fas
          description:  <span style="font-size:90%">Building websites using tools like React.</span><br><br>
        - name: App Development
          icon: app-store-ios
          icon_pack: fab
          description:  <span style="font-size:90%">App development using Android Studio!</span><br><br>

  
  - block: collection
    content:
      title: Latest Work
      subtitle:
      text:
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 
      order: desc
      page_type: work
    design:
      view: community/custom_view_joonhyuk1
      columns: '2'
      background:
        # Choose a color such as from https://html-color-codes.info
        color: '#BFFF00'
        # Text color (true=light, false=dark, or remove for the dynamic theme color).
        text_color_light: true

  - block: collection
    content:
      title: Latest Team Project
      subtitle:
      text:
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: team
    design:
      view: community/custom_view_joonhyuk2
      columns: '2'
      background:
        # Choose a color such as from https://html-color-codes.info
        color: '#3ADF00'
        # Text color (true=light, false=dark, or remove for the dynamic theme color).
        text_color_light: true
    advanced:
      css_style: "text-align: center;"


  - block: collection
    content:
      title: Latest Solo Project
      subtitle:
      text:
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: solo
    design:
      view: card
      columns: '2'
      background:
        # Choose a color such as from https://html-color-codes.info
        color: '#04B45F'
        # Text color (true=light, false=dark, or remove for the dynamic theme color).
        text_color_light: true
    advanced:
      css_style: "text-align: center;"


---
