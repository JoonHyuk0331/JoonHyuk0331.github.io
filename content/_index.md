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
        -short introduce-
        I am a student studying computer science and am interested in web programming.
      cta:
        label: Download Résumé
        url: /uploads/joon_resume.pdf

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
      contact_links:
        - icon: github
          icon_pack: fab
          name: go to github page
          link: https://github.com/JoonHyuk0331
      autolink: true

  - block: slider
    content:
      slides:
        - title: <span class="text-overlay">coding</span>
          content: <span style="font-size:70%">study code</span>
          align: justify
          background:
            image:
              filename: code1.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'

        - title: <span style="font-size:70%">AI</span>
          content: <span style="font-size:70%">learning ai!</span>
          align: justify
          background:
            image:
              filename: code2.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'

        - title: <span style="font-size:70%">Cat</span>
          content: <span style="font-size:70%">Look at the cute cat</span>
          align: justify
          background:
            image:
              filename: catimage.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'
    design:
      slide_height: '350px'
      slide_width: '100px'
      is_fullscreen: false
      loop: true
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
          description: <span style="font-size:90%">Collecting and utilizing large amounts of data through web crawling.</span><br><br>
        - name: Mathematics
          icon: calculator
          icon_pack: fas
          description: <span style="font-size:90%">Mathematical theories related to AI, such as linear algebra.</span><br><br>
        - name: Backend Development
          icon: server
          icon_pack: fas
          description: <span style="font-size:90%">Server construction and database utilization.</span><br><br>
        - name: Frontend Development
          icon: laptop
          icon_pack: fas
          description: <span style="font-size:90%">Building websites using tools like React.</span><br><br>
        - name: App Development
          icon: app-store-ios
          icon_pack: fab
          description: <span style="font-size:90%">App development using Android Studio!</span><br><br>

  - block: collection
    content:
      title: Latest Work
      count: 3
      filters:
        exclude_featured: false
      design:
        view: card
        columns: '2'
        background:
          color: '#BFFF00'
          text_color_light: true

  - block: collection
    content:
      title: Latest Team Project
      count: 3
      filters:
        exclude_featured: false
      design:
        view: community/custom_card
        columns: '2'
        background:
          color: '#3ADF00'
          text_color_light: true
      advanced:
        css_style: "text-align: justify;"

  - block: collection
    content:
      title: Latest Solo Project
      count: 3
      filters:
        exclude_featured: false
      design:
        view: card
        columns: '2'
        background:
          color: '#04B45F'
          text_color_light: true
      advanced:
        css_style: "text-align: justify;"
---
