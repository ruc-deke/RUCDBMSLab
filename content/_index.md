---
# Leave the homepage title empty to use the site title
title:
date: 2024-09-30
type: landing

sections:
  - block: hero
    content:
      title: |
        RUC DBMS
        Research Group
      image:
        filename: icon.png
      text: |
        <br>

        中国人民大学数据库系统研究组是由卢卫教授所领导的研究与工程兼备的研究组。实验室专注于数据库基础理论、云原生数据库、数据库系统测试、AI4DB等问题的研究，并取得了一系列重要研究成果。研究方向介绍:

        <h2>数据库系统/云原生数据库研究</h2>

        <h2>数据库系统测试</h2>

        <h2>AI4DB</h2>
  
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
      title: Latest Research Achievements
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'paper-conference'
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
