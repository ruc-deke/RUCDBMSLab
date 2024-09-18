---
title: 'MSQL: Efficient Similarity Search in Metric Spaces using SQL'
profile: false
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Wei Lu
  - Jiajia Hou
  - Ying Yan
  - Meihui Zhang
  - Xiaoyong Du
  - Thomas Moscibroda
# Author notes (optional)

# 论文发表时间, 格式为xxxx-xx-xxTxx:xx:xxZ, 需要完整填写，否则可能导致网站显示异常
date: "2017-10-06T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2017-10-06T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# 论文类型，会议为paper-conference，期刊为journal-article
publication_types: ['journal-article']

# Publication name and optional abbreviated publication name.
publication: In *VLDBJ*
publication_short: ""

# 文章摘要
abstract: Similarity search is a primitive operation that arises in a large variety of database applications. Typical examples include identifying articles with similar titles, finding similar images and music in a large digital object repository, etc. While there exist a wide spectrum of access methods for similarity queries in metric spaces, a practical solution that can be fully supported by existing RDBMS with high efficiency still remains an open problem. In this paper, we present MSQL, a practical solution for answering similarity queries in metric spaces fully using SQL. To the best of our knowledge, MSQL enables users to find similar objects by submitting SELECT-FROM-WHERE statements only. MSQL provides a uniform indexing scheme based on a standard built-in B+ -tree index, with the ability to accelerate the query processing using index seek. Various query optimization techniques are incorporated in MSQL to significantly reduce CPU and I/O cost. We deploy MSQL on top of PostgreSQL. Extensive experiments on various real data sets demonstrate MSQL’s benefits, performing up to two orders of magnitude faster than existing domain-specific SQL-based solutions and being comparable to native solutions.

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
url_pdf: 'http://iir.ruc.edu.cn/groups/database/res/VLDBJ2017.pdf'
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
