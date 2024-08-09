---
title: 'RCBench: an RDMA-enabled transaction framework for analyzing concurrency control algorithms'
profile: false
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Hongyao Zhao
  - Jingyao Li
  - Wei Lu
  - Qian Zhang
  - Wanqing Yang
  - Jiajia Zhong
  - Meihui Zhang
  - Haixiang Li
  - Xiaoyong Du
  - Anqun Pan
# Author notes (optional)

date: "2023-12-14T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2023-12-14T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['journal-conference']

# Publication name and optional abbreviated publication name.
publication: in *VLDBJ*
publication_short: ""

abstract: Distributed transaction processing over the TCP/IP network suffers from the weak transaction scalability problem, i.e., its performance drops significantly when the number of involved data nodes per transaction increases. Although quite a few of works over the high-performance RDMA-capable network are proposed, they mainly focus on accelerating distributed transaction processing, rather than solving the weak transaction scalability problem. In this paper, we propose RCBench, an RDMA-enabled transaction framework, which serves as a unified evaluation tool for assessing the transaction scalability of various concurrency control algorithms. The usability and advancement of RCBench primarily come from the proposed concurrency control primitives, which facilitate the convenient implementation of RDMA-enabled concurrency control algorithms. Various optimization principles are proposed to ensure that concurrency control algorithms in RCBench can fully benefit from the advantages offered by RDMA-capable networks. We conduct extensive experiments to evaluate the scalability of mainstream concurrency control algorithms. The results show that by exploiting the capabilities of RDMA, concurrency control algorithms in RCBench can obtain 42X performance improvement, and transaction scalability can be achieved in RCBench..

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/dbiir/RCBench'

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
