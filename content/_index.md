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

      中国人民大学数据库系统研究组（Database System Research Group，简称DBSys）是由卢卫教授领导的研究与工程兼备的研究组是数据工程与知识工程教育部重点实验室（DEKE，主任为杜小勇教授）的重要组成部分，隶属于中国人民大学信息学院计算机系。DBSys实验室以实际应用需求为牵引，聚焦数据库系统（包括云原生数据库、分布式数据库、智能数据库、图数据库等）关键技术研究与学术前沿技术创新；探索各类数据库原型系统研制，将创新技术集成到原型系统中，并进行系统开源；与数据库头部企业开展产学研用多方合作，将创新技术集成到企业的真实系统中进行成果验证，取得了一系列重要研究成果。

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
