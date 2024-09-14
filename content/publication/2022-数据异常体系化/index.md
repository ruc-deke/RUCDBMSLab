---
title: '数据库管理系统中数据异常体系化定义与分类'
profile: false
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - 李海翔
  - 李晓燕
  - 刘畅
  - 杜小勇
  - 卢卫
  - 潘安群
# Author notes (optional)

date: "2022-03-01T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2022-03-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['journal-conference']

# Publication name and optional abbreviated publication name.
publication: in *软件学报*
publication_short: ""

abstract: 数据异常尚没有统一的定义, 其含义是指可能破坏数据库一致性状态的特定数据操作模式. 已知的数据
异常有脏写、脏读、不可重复读、幻读、丢失更新、读偏序和写偏序等. 为了提高并发控制算法的效率, 数据异
常也被用于定义隔离级别, 采用较弱的隔离级别以提高事务处理系统的效率. 体系化地研究了数据异常以及对应
的隔离级别, 发现了 22 种未被其他文献报告过的新的数据异常, 并对全部数据异常进行分类. 基于数据异常的分
类, 提出了新的且不同粒度的隔离级别体系, 揭示基于数据异常定义隔离级别的规律, 使得对于数据异常和隔离
级别等相关概念的认知可以更加简明.

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.jos.org.cn/jos/article/abstract/6442'
url_code: 'https://github.com/Tencent/3TS'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
