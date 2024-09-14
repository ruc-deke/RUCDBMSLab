---
title: '分布式数据库多级一致性统一建模理论研究'
profile: false
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - 水治禹
  - 卢卫
  - 赵展浩
  - 何粤阳
  - 张孝
  - 杜小勇
# Author notes (optional)

date: "2023-05-01T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2023-05-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['journal-conference']

# Publication name and optional abbreviated publication name.
publication: in *软件学报*
publication_short: ""

abstract: 分布式数据库系统出现了支持多协调器和多副本存储的新架构, 这给事务调度的正确性带来了新的挑战, 包括缺少中心协调器带来的新数据异常以及多副本机制带来的读取数据一致性等问题. 基于事务隔离级别和分布式系统一致性协议的定义, 为多协调器多副本分布式数据库的事务多级一致性构建了一个混合依赖图模型. 该形式化模型为事务的正确调度提供具有鲁棒性的评价标准, 可以方便地对数据库事务调度情况进行动态或静态分析检验.

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.jos.org.cn/jos/article/abstract/6460'
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
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
