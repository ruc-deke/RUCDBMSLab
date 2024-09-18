---
title: 'Efficient and Scalable Mining of Frequent Subgraphs Using Distributed Graph Processing Systems'
profile: false
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Tongtong Wang
  - Hao Huang
  - Wei Lu
  - Zhe Peng
  - Xiaoyong Du
# Author notes (optional)

# 论文发表时间, 格式为xxxx-xx-xxTxx:xx:xxZ, 需要完整填写，否则可能导致网站显示异常
date: "2018-05-13T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2018-05-13T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# 论文类型，会议为paper-conference，期刊为journal-article
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *DASFAA*
publication_short: ""

# 文章摘要
abstract: Mining frequent subgraphs in large scale graph data sets helps reveal underlying knowledge. Since the mining approaches in centralized systems are often bottlenecked on calculation capacity, many parallelized solutions based on the MapReduce framework are proposed to scale out the mining process, which usually extracts frequent subgraphs in an iterative way. Nonetheless, the efficiency and scalability of these MapReduce based approaches are still bounded by the communication cost for passing the intermediate results and the unbalanced workload after a few iterations. In this paper, we propose an efficient and scalable framework for frequent subgraph mining by using distributed graph processing systems. It adopts a message-passing-free scheme among workers to reduce the communication cost, and utilizes a task scheduler to dynamically balance the workload. Experimental results on both synthetic and real-world data sets verify the efficacy of our proposed framework.

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
url_pdf: 'https://link.springer.com/chapter/10.1007/978-3-319-91452-7_57'
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
