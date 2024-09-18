---
title: 'False data separation for data security in smart grids'
profile: false
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Hao Huang
  - Qian Yan
  - Yao Zhao
  - Wei Lu
  - Zhenguang Liu
  - Zongpeng Li
# Author notes (optional)

# 论文发表时间, 格式为xxxx-xx-xxTxx:xx:xxZ, 需要完整填写，否则可能导致网站显示异常
date: "2017-01-18T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-18T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# 论文类型，会议为paper-conference，期刊为journal-article
publication_types: ['journal-article']

# Publication name and optional abbreviated publication name.
publication: In *KAIS*
publication_short: ""

# 文章摘要
abstract: The smart grid is emerging as an efficient paradigm for electric power generation, transmission, and consumption, based on optimized decision making and control that leverage the measurement data of sensors and meters in the grid. False data injection is a new type of power grid attacks aiming to tamper such important data. For the security and robustness of the grid, it is critical to separate the false data injected by such attacks and recover the original measurement data. Nonetheless, the existing approaches often neglect the true changes on original measurement data that are caused by the real perturbations on grid states and hence have a risk of removing these true changes as injected false data during the data recovery. In this paper, we preserve these true changes by modeling the false data problem as a rank-bounded L1 norm optimization and propose both offline and online algorithms to filter out the injected false data and recover original measurement data. Trace-driven simulations verify the efficacy of our solution.

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
url_pdf: 'https://link.springer.com/article/10.1007/s10115-016-1019-8'
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
