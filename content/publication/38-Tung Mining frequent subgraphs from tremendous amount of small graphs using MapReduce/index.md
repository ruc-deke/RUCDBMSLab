---
title: 'Mining frequent subgraphs from tremendous amount of small graphs using MapReduce'
profile: false
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zhe Peng
  - Tongtong Wang
  - Wei Lu
  - Hao Huang
  - Xiaoyong Du
  - Feng Zhao
  - Anthony K. H. Tung
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
publication: In *KAIS*
publication_short: ""

# 文章摘要
abstract: Frequent subgraph mining from a tremendous amount of small graphs is a primitive operation for many data mining applications. Existing approaches mainly focus on centralized systems and suffer from the scalability issue. Consider the increasing volume of graph data and mining frequent subgraphs is a memory-intensive task, it is difficult to tackle this problem on a centralized machine efficiently. In this paper, we therefore propose an efficient and scalable solution, called MRFSE, using MapReduce. MRFSE adopts the breadth-first search strategy to iteratively extract frequent subgraphs, i.e., all frequent subgraphs with i + 1 edges are generated based on frequent subgraphs with i edges at the ith iteration. In our design, existing frequent subgraph mining techniques in centralized systems can be easily extended and integrated. More importantly, new frequent subgraphs are generated without performing any isomorphism test which is costly and imperative in existing frequent subgraph mining techniques. Besides, various optimization techniques are proposed to further reduce the communication and I/O cost. Extensive experiments conducted on our in-house clusters demonstrate the superiority of our proposed solution in terms of both scalability and efficiency.
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
url_pdf: 'https://link.springer.com/article/10.1007/s10115-017-1104-7'
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
