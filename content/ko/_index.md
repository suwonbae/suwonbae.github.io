---
title:
date: 2024-01-01
type: landing

sections:
  - block: hero
    content:
      title: 계산과학 및 응용역학 연구실
      text: | 
        <br>

        우리 연구실 홈페이지에 오신 것을 환영합니다.

      cta:
        label: 구성원
        url: people
      cta_alt:
        label: 연구분야
        url: research
    design:
      background:
        color: 'white'
        text_color_light: false

  - block: collection
    content:
      title: 최근 소식
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

  - block: collection
    content:
      title: 최근 논문
      text: ""
      count: 5
      filters:
        folders:
          - publication
      order: desc
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="구성원" %}}
    design:
      columns: '1'
---
