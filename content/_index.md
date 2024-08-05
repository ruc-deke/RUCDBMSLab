---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        RUC DBMS
        Research Group
      image:
        filename: graduated2.jpg
      text: |
        <br>

        中国人民大学数据库系统研究组（RUC DBMS Research Group）是由杜小勇教授所领导的研究与工程兼备的研究组，是数据工程与知识工程教育部重点实验室（DEKE）的重要组成部分，隶属于中国人民大学信息学院计算机系。实验室专注于数据库基础理论、大数据系统研制、云原生数据库等问题的研究，并取得了一系列重要研究成果，部分成果已应用于社会治理、企业应用等多个领域。欢迎有志的同学加盟！
  
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
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: contact2024.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Research Achievements
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
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
