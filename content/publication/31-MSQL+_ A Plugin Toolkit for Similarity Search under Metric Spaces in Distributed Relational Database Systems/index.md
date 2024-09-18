---
title: 'MSQL+: A Plugin Toolkit for Similarity Search under Metric Spaces in Distributed Relational Database Systems'
profile: false
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Wei Lu
  - Zhiyu Shui
  - Xinyi Zhang
  - Zhe Peng
  - Xiao Zhang
  - Xiaoyong Du
  - Hao Huang
  - Xiaoyu Wang
  - Anqun Pan
  - Haixiang Li
# Author notes (optional)

# 论文发表时间, 格式为xxxx-xx-xxTxx:xx:xxZ, 需要完整填写，否则可能导致网站显示异常
date: "2018-08-01T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2018-08-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# 论文类型，会议为paper-conference，期刊为journal-article
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *VLDB*
publication_short: ""

# 文章摘要
abstract: Similarity search is a primitive operation in various database applications. Thus far, a large number of access methods have been proposed to accelerate the similarity query processing. Nonetheless, these methods mostly focus on developing standalone systems by proposing new indices. Given the fact that existing RDBMS merely support traditional indices, it is of great necessity and practical importance to develop a standard RDBMS built-in index based approach to speeding up the query processing. In this demonstration, we introduce MSQL+, a plugin toolkit that enable users to answer similarity queries in metric spaces simply using standard SQL statements. This toolkit can help existing RDBMS to effectively and efficiently handle with big data due to the following three advantages. First, MSQL+ enables users to find similar objects by submitting SELECT-FROM-WHERE statements so that it can be easily integrated into existing RDBMS. Second, MSQL+ works in a more general data space. Objects of any type can be indexed by B+-trees and the query processing can be boosted by using index seeks, as long as the similarity function is metric. Third, MSQL+ supports the parallelization of both pre-processing and query processing in distributed RDBMS.

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
url_pdf: 'https://dl.acm.org/doi/abs/10.14778/3229863.3236237'
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
