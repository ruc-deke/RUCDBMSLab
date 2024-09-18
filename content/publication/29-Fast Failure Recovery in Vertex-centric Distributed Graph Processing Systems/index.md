---
title: 'Fast Failure Recovery in Vertex-centric Distributed Graph Processing Systems'
profile: false
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Wei Lu
  - Yanyan Shen
  - Tongtong Wang
  - Meihui Zhang
  - Xiaoyong Du
# Author notes (optional)

# 论文发表时间, 格式为xxxx-xx-xxTxx:xx:xxZ, 需要完整填写，否则可能导致网站显示异常
date: "2018-06-04T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2018-06-04T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# 论文类型，会议为paper-conference，期刊为journal-article
publication_types: ['journal-article']

# Publication name and optional abbreviated publication name.
publication: In *TKDE*
publication_short: ""

# 文章摘要
abstract: There is a growing need for distributed graph processing systems to have many more compute nodes processing graph-based Big Data applications, which, however, increases the chance of node failures. To address the issue, we propose a novel recovery scheme to accelerate the recovery process by parallelizing the recomputation. Once a failure occurs, all recomputations are confined to subgraphs that originally reside in the failed compute nodes. When the recovery starts, these subgraphs are reassigned to another set of compute nodes, where the recomputation over these subgraphs are conducted in parallel. To minimize the recovery latency, we also develop a reassignment strategy, from these subgraphs to the replaced compute nodes, by properly leveraging the computation and communication cost. We integrate the proposed recovery scheme into Giraph system, a widely used graph processing system. The experimental results over a variety of real graph datasets demonstrate that our proposed recovery scheme outperforms existing recovery methods by up to 30x on a cluster of 40 compute nodes.

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
url_pdf: 'https://ieeexplore.ieee.org/abstract/document/8371278'
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
