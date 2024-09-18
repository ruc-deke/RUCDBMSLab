---
title: 'Efficient Time-interval Data Extraction in MVCC-based RDBMS'
profile: false
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Haixiang Li
  - Zhanhao Zhao
  - Yijian Cheng
  - Wei Lu
  - Xiaoyong Du
  - Anqun Pan 
# Author notes (optional)

# 论文发表时间, 格式为xxxx-xx-xxTxx:xx:xxZ, 需要完整填写，否则可能导致网站显示异常
date: "2018-04-11T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2018-04-11T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# 论文类型，会议为paper-conference，期刊为journal-article
publication_types: ['journal-article']

# Publication name and optional abbreviated publication name.
publication: In *WWWJ*
publication_short: ""

# 文章摘要
abstract: Account reconciliation is the core business in banks and game companies. It regularly examines the account balance with the bank or expense statement for every user and reports the daily, weekly, or monthly balance. Once an account imbalance occurs, it is necessary to efficiently trace the transactions that possibly destroy the account balances. To help efficiently trace this kind of transactions, in this paper, we investigate the problem of doing efficient time-interval data extraction in MVCC-based RDBMS, i.e., extracting the incremental data that are valid between a given time interval in MVCC-based RDBMS. To this end, we propose a snapshot-based method to extract incremental data based on the fact that each record is inherently associated with lifetime, indicating whether the record can be accessed or not for a given time interval. We elaborate how to integrate our method into MySQL, an open-sourced RDBMS, and propose a declarative way to fetch the incremental data. Several optimization techniques are proposed to boost the extraction performance. Extensive experiments are conducted over the standardized Sysbench benchmark to show that our proposed method is robust and efficient.

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
url_pdf: 'http://iir.ruc.edu.cn/groups/database/res/WWW2018.pdf'
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
