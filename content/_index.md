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
        filename: jjj.jpg
      text: |
        <br>
        
        I am a student studying computer science and am interested in web programming.
  
  - block: slider
    content:
      slides:

      - title: <span style="font-size:70%">Recruit</span>
        content: <span style="font-size:70%">Interested in MacsLAB?</span>
        align: center
        background:
          image:
            filename: sample_images_00.png
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: user
          icon_pack: fas
          text: <span style="font-size:60%">Join Us</span>
          text-color: '#000'
          url: contact

      - title: <span style="font-size:70%">AI</span>
        content: <span style="font-size:70%">의료/항공우주/컨텐츠 등 특성화 분야에 적용 가능한 AI 기술 개발<span style="font-size:70%">
        align: center
        background:
          image:
            filename: sample_images_01.png
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Healthcare</span>
        content: <span style="font-size:70%">의료 및 헬스케어 분야에 적용 가능한 AI 기술 개발</span>
        align: center
        background:
          image:
            filename: sample_images_02.png
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Mathematics</span>
        content: <span style="font-size:70%">AI와 관련된 수학 및 최적화 이론 연구</span>
        align: center
        background:
          image:
            filename: sample_images_03.png
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Development</span>
        content: <span style="font-size:70%">기반 기술을 활용한 Full-Stack 어플리케이션 개발</span>
        align: center
        background:
          image:
            filename: sample_images_04.png
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
      title: Latest News
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
      page_type: post
    design:
      view: card
      columns: '1'
      background:
        # Choose a color such as from https://html-color-codes.info
        color: 'navy'
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
        view: community/custom_card
        columns: '2'
      advanced:
        css_style: "text-align: center;"

  - block: awards
    content:
      title: Awards
      username: admin


---
