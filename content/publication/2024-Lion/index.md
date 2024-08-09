---
title: 'Lion: Minimizing Distributed Transactions through Adaptive Replica Provision'
profile: false
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Qiushi Zheng
  - Zhanhao Zhao
  - Wei Lu
  - Chang Yao
  - Yuxing Chen
  - Anqun Pan 
  - Xiaoyong Du
# Author notes (optional)

# 论文发表时间, 格式为xxxx-xx-xxTxx:xx:xxZ, 需要完整填写，否则可能导致网站显示异常
date: "2024-02-01T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2024-02-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# 论文类型，会议为paper-conference，期刊为journal-article
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *ICDE*
publication_short: ""

# 文章摘要
abstract: Distributed transaction processing often involves multiple rounds of cross-node communications, and therefore, tends to be slow. To improve performance, existing approaches convert distributed transactions into single-node transactions by either migrating co-accessed partitions onto the same nodes or establishing a super node housing replicas of the entire database. However, migration-based methods might cause transactions to be blocked due to waiting for data migration, while the super node can become a bottleneck. In this paper, we present Lion, a novel transaction processing protocol that utilizes partition-based replication to reduce the occurrence of distributed transactions. Inspired by the fact that modern distributed databases horizontally partition data, with each partition having multiple replicas, Lion aims to assign a node with one replica from each partition involved in a given transaction's read or write operations. To ensure such a node is available, we propose an adaptive replica provision mechanism, enhanced with an LSTM-based workload prediction algorithm, to determine the appropriate node for locating replicas of co-accessed partitions. The adaptation of replica placement is conducted preemptively and asynchronously, thereby minimizing its impact on performance. By employing this adaptive replica placement strategy, we ensure that the majority of transactions can be efficiently processed on a single node without additional overhead. Only a small fraction of transactions will need to be treated as regular distributed transactions when such a node is unavailable. Consequently, Lion effectively minimizes distributed transactions, while avoiding any disruption caused by data migration or the creation of a super node. We conduct extensive experiments to compare Lion against various transaction processing protocols. The results show that Lion achieves up to 2.7x higher throughput and 76.4% better scalability against these state-of-the-art approaches.

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
url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10598008'
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
