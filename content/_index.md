---
title:
date: 2024-01-01
type: landing

sections:
  - block: hero
    content:
      title: BAE Lab
      text: |
        <br>

        We are a research group in the [School of Mechanical Engineering](https://me.pusan.ac.kr) at **Pusan National University**.

        Our goal is to understand the complex behaviors of polymers via bottom-up, predictive modeling and reflect this knowledge into material design principles. We work at the intersection of **computational mechanics**, **polymer physics**, and **data-driven materials design**.
      cta:
        label: Meet the team
        url: people
      cta_alt:
        label: Our research
        url: research
    design:
      background:
        color: '#1a1a2e'
        text_color_light: true

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
