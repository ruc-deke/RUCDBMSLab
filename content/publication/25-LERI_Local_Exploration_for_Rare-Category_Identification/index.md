---
title: 'LERI: Local Exploration for Rare-Category Identification'
profile: false
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Hao Huang
  - Qian Yan
  - Wei Lu
  - Huaizhong Lin
  - Yunjun Gao
  - Lei Chen 
# Author notes (optional)

# 论文发表时间, 格式为xxxx-xx-xxTxx:xx:xxZ, 需要完整填写，否则可能导致网站显示异常
date: "2019-04-17T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2019-04-17T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# 论文类型，会议为paper-conference，期刊为journal-article
publication_types: ['journal-article']

# Publication name and optional abbreviated publication name.
publication: In *TKDE*
publication_short: ""

# 文章摘要
abstract: To identify the data examples of rare categories that form small compact clusters in large data sets, existing approaches mostly require enough labeled data examples as a training set to learn a classifier, assuming that the rare-category clusters are spherical or nearly spherical. Nonetheless, a large enough training set is usually difficult to obtain in practice, and rare categories in many real-world applications often form small compact clusters with arbitrary shapes. In this paper, we investigate how to identify all data examples of a rare category with an arbitrary shape based on only one seed (i.e., a labeled rare-category data example). Instead of finding a compact and spherical local region around the seed, we locally explore the data set from the seed by continuously searching and visiting the k-nearest neighbors of each newly visited data example. The local exploration connects the data examples in the objective rare category by the relationship of k-nearest neighbors, and meanwhile, suspected external data examples are filtered out if they are not close enough to any visited data example. Experimental results on both synthetic and real-world data sets are conducted, and the results verify the effectiveness and efficiency of our approach.

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
url_pdf: 'https://ieeexplore.ieee.org/abstract/document/8693540'
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
