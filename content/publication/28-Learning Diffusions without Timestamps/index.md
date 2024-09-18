---
title: 'Learning Diffusions without Timestamps'
profile: false
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Hao Huang
  - Qian Yan
  - Ting Gan
  - Di Niu
  - Wei Lu
  - Yunjun Gao
# Author notes (optional)

# 论文发表时间, 格式为xxxx-xx-xxTxx:xx:xxZ, 需要完整填写，否则可能导致网站显示异常
date: "2019-07-17T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2019-07-17T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# 论文类型，会议为paper-conference，期刊为journal-article
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *AAAI*
publication_short: ""

# 文章摘要
abstract: To learn the underlying parent-child influence relationships between nodes in a diffusion network, most existing approaches require timestamps that pinpoint the exact time when node infections occur in historical diffusion processes. In many real-world diffusion processes like the spread of epidemics, monitoring such infection temporal information is often expensive and difficult. In this work, we study how to carry out diffusion network inference without infection timestamps, using only the final infection statuses of nodes in each historical diffusion process, which are more readily accessible in practice. Our main result is a probabilistic model that can find for each node an appropriate number of most probable parent nodes, who are most likely to have generated the historical infection results of the node. Extensive experiments on both synthetic and real-world networks are conducted, and the results verify the effectiveness and efficiency of our approach.

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
url_pdf: 'https://ojs.aaai.org/index.php/AAAI/article/view/3833'
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
