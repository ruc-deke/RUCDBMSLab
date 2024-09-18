---
title: 'Eficient Distributed Transaction Processing in Heterogeneous Networks'
profile: false
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Qian Zhang
  - Jingyao Li
  - Hongyao Zhao
  - Quanqing Xu
  - Wei Lu
  - Jinliang Xiao
  - Fusheng Han
  - Chuanhui Yang
  - Xiaoyong Du
# Author notes (optional)

date: "2023-02-01T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2023-02-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['journal-conference']

# Publication name and optional abbreviated publication name.
publication: in *VLDB*
publication_short: ""

abstract:  Countrywide and worldwide business, like gaming and social networks, drives the popularity of inter-data-center transactions. To support inter-data-center transaction processing and data center fault tolerance simultaneously, existing protocols suffer from significant performance degradation due to high-latency and unstable networks. In this paper, we propose RedT, a novel distributed transaction processing protocol that works in heterogeneous networks. In detail, nodes within a data center are inter-connected via the RDMA-capable network and nodes across data centers are inter-connected via TCP/IP networks. RedT extends two-phase commit (2PC) by decomposing transactions into sub-transactions in terms of the data center granularity, and proposing a pre-write-log mechanism that is able to reduce the number of inter-data-center round-trips from a maximal of 6 to 2. Extensive evaluation against state-of-the-art protocols shows that RedT can achieve up to 1.57x higher throughputs and 0.56x lower latency.

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/10.14778/3583140.3583153'
url_code: 'https://github.com/dbiir/RedT'

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
