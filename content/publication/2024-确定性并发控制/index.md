---
title: '基于确定性并发控制的云原生多写技术(云原生数据库技术与系统)'
profile: false
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - 洪殷昊
  - 赵泓尧
  - 王乙霖
  - 史心悦
  - 卢卫
  - 杨尚
  - 杜胜
# Author notes (optional)

date: "2024-05-27T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2024-05-27T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['journal-conference']

# Publication name and optional abbreviated publication name.
publication: in *软件学报*
publication_short: ""

abstract: 云原生数据库具有开箱即用、弹性伸缩、按需付费等优势, 是目前学术界和工业界的研究热点. 当前, 云原生数据库仅支持"一写多读", 即读写事务集中在单一的读写节点, 只读事务分散到多个只读节点. 将读写事务集中在单一的读写节点, 制约了系统的读写事务处理能力, 难以满足读写密集型业务需求. 为此, 本文提出了D3C(deterministic concurrency control cloud database)架构, 通过设计基于确定性并发控制的云原生数据库事务处理机制来突破一写多读的限制, 支持多个读写节点并发执行读写事务. 其中 D3C 将事务分拆为子事务, 并根据预先确定的全局顺序在各节点独立执行这些子事务, 以满足多个读写节点上事务执行的可串行化. 此外本文提出了基于多版本机制的异步批量数据持久化等机制保证事务处理的性能, 并提出基于一致性点的故障恢复机制实现高可用. 实验表明, D3C 在满足云原生数据库关键需求的同时, 在写密集场景下能达到一写多读性能的 5.1 倍.

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.jos.org.cn/jos/article/abstract/7281'
url_code: 'https://github.com/dbiir/Cloud-Deneva.git'

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
