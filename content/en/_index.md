---
title:
date: 2024-01-01
type: landing

sections:
  - block: hero
    content:
      title: Computational Science and Applied Mechanics Lab.
      text: |
        <br>

        Welcome to BAE Research Group page.

      cta:
        label: Meet the team
        url: people
      cta_alt:
        label: Our research
        url: research
    design:
      background:
        color: 'white'
        text_color_light: false

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

  - block: collection
    content:
      title: Recent Publications
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
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
