---
title: 'T-SQL: A Lightweight Implementation to Enable Built-in Temporal Support in MVCC-Based RDBMSs'
profile: false
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zhanhao Zhao
  - Wei Lu
  - Hongyao Zhao
  - Zongyan He
  - Haixiang Li
  - Meihui Zhang
  - Anqun Pan
  - Xiaoyong Du
# Author notes (optional)

date: "2021-05-19T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2021-05-19T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['journal-conference']

# Publication name and optional abbreviated publication name.
publication: in *TKDE*
publication_short: ""

abstract:  The adoption of temporal expressions into SQL:2011 has continuously driven the extensions of temporal support in relational database systems (a.b.a. RDBMSs). In this paper, we present T-SQL , a lightweight yet efficient built-in temporal implementation in RDBMSs. T-SQL entirely relies on multi-version concurrency control (MVCC), widely adopted in RDMBSs, to manage temporal data . For temporal data, current records are maintained in legacy databases, and historical records , i.e., previous versions of current records (if any), which used to be periodically reclaimed are separately maintained in KV stores. To enable temporal query processing under SQL:2011, we extend the query engine in legacy RDBMSs to support query processing over either current records or historical records or both. Further, regarding temporal data are ever-increasing, we propose various optimizations to reduce the storage overhead of KV stores while keeping efficient query performance. We elaborate a publicly available implementation on how to integrate T-SQL into both centralized and distributed RDBMSs. We conduct extensive experiments on both YCSB and TPC-series benchmarks by comparing T-SQL with other temporal database systems. The results show that T-SQL is both lightweight and efficient.

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/9435995'
url_code: 'https://github.com/dbiir/T-SQL'

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
