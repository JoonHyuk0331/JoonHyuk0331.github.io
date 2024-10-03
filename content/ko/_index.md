---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        김준혁
      image:
        filename: webmypic.jpg
      text: |
        <br>
        -짧은 소개-
        웹 프로그래밍에 관심있는 컴퓨터공학과 학생입니다. 
      cta:
        label: 이력서 다운로드
        url: /uploads/joon_resume.pdf
        #icon_pack: fas
        #icon: download
      # Optionally, add an alternative CTA link


  - block: contact
    content:
      title: Contact
      text: |-
        <br> <span style="font-size:95%">전북대학교 한빛관에 거주중입니다.</span> <br>
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

      - title: <span class="text-overlay">코딩</span>
        content: <span style="font-size:70%">즐거운 코딩공부e</span>
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
        content: <span style="font-size:70%">AI 학습!<span style="font-size:70%">
        align: center
        background:
          image:
            filename: code2.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">고양이</span>
        content: <span style="font-size:70%">귀여운 고양이를 보십시오</span>
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
      title: <span style="font-size:75%">관심분야</span>
      text: 다음과 같은 분야들에 관심이 많습니다.<br><br><br><br>
      items:
        - name: AI
          icon: code-branch
          icon_pack: fas
          description: <span style="font-size:90%">머신러닝 컴퓨터비전 자연어처리같은 ai분야에 관심이 있습니다.</span><br><br>
        - name: 웹 크롤링
          icon: globe
          icon_pack: fas
          description:  <span style="font-size:90%">웹 크롤링을 통해 대용량 데이터를 수집합니다</span><br><br>
        - name: 수학
          icon: calculator
          icon_pack: fas
          description:  <span style="font-size:90%">선형대수학 같은 ai관련 수학</span><br><br>
        - name: 백엔드 개발 
          icon: server
          icon_pack: fas
          description:  <span style="font-size:90%">서버 구축 및 데이터베이스 최적화.</span><br><br>
        - name: 프론트 개발
          icon: laptop
          icon_pack: fas
          description:  <span style="font-size:90%">다양한 라이브러리를 통한 웹 제작</span><br><br>
        - name: 앱 개발
          icon: app-store-ios
          icon_pack: fab
          description:  <span style="font-size:90%">안드로이드 스튜디오를 통한 앱 개발</span><br><br>

  
  - block: collection
    content:
      title: 최근 작업들
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
      title: 최근 팀 프로젝트
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
      title: 최근 개인 프로젝트
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
