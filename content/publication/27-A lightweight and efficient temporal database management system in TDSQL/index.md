---
title: 'A lightweight and efficient temporal database management system in TDSQL'
profile: false
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Wei Lu
  - Zhanhao Zhao
  - Xiaoyu Wang
  - Haixiang Li
  - Zhenmiao Zhang
  - Zhiyu Shui 
  - Sheng Ye
  - Anqun Pan
  - Xiaoyong Du
# Author notes (optional)

# 论文发表时间, 格式为xxxx-xx-xxTxx:xx:xxZ, 需要完整填写，否则可能导致网站显示异常
date: "2019-08-01T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2019-08-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# 论文类型，会议为paper-conference，期刊为journal-article
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *VLDB*
publication_short: ""

# 文章摘要
abstract: Driven by the recent adoption of temporal expressions into SQL:2011, extensions of temporal support in conventional database management systems (a.b.a. DBMSs) have re-emerged as a research hotspot. In this paper, we present a lightweight yet efficient built-in temporal implementation in Tencent's distributed database management system, namely TDSQL. The novelty of TDSQL's temporal implementation includes (1) a new temporal data model with the extension of SQL:2011, (2) a built-in temporal implementation with various optimizations, which are also applicable to other DBMSs, and (3) a low-storage-consumption in which only data changes are maintained. For the repeatability purpose, we elaborate the integration of our proposed techniques into MySQL. We conduct extensive experiments on both real-life dataset and synthetic TPC benchmarks by comparing TD-SQL with other temporal databases. The results show that TDSQL is lightweight and efficient.

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# 论文和代码链接，如果没有代码链接则直接将url_code一行删除
url_pdf: 'https://dl.acm.org/doi/abs/10.14778/3352063.3352122'
url_code: ''

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
# 可以不填
projects:
  - example
# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# 可以不填
slides: example
---
