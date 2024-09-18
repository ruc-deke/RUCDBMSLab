---
title: 'Fast and Scalable Distributed Set Similarity Joins for Big Data Analytics'
profile: false
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Chuitian Rong
  - Chunbin Lin
  - Yasin N. Silva
  - Jianguo Wang
  - Wei Lu
  - Xiaoyong Du
# Author notes (optional)

# 论文发表时间, 格式为xxxx-xx-xxTxx:xx:xxZ, 需要完整填写，否则可能导致网站显示异常
date: "2017-04-19T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2017-04-19T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# 论文类型，会议为paper-conference，期刊为journal-article
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *ICDE*
publication_short: ""

# 文章摘要
abstract: Set similarity join is an essential operation in big data analytics, e.g., data integration and data cleaning, that finds similar pairs from two collections of sets. To cope with the increasing scale of the data, distributed algorithms are called for to support large-scale set similarity joins. Multiple techniques have been proposed to perform similarity joins using MapReduce in recent years. These techniques, however, usually produce huge amounts of duplicates in order to perform parallel processing successfully as MapReduce is a shared-nothing framework. The large number of duplicates incurs on both large shuffle cost and unnecessary computation cost, which significantly decrease the performance. Moreover, these approaches do not provide a load balancing guarantee, which results in a skewness problem and negatively affects the scalability properties of these techniques. To address these problems, in this paper, we propose a duplicatefree framework, called FS-Join, to perform set similarity joins efficiently by utilizing an innovative vertical partitioning technique. FS-Join employs three powerful filtering methods to prune dissimilar string pairs without computing their similarity scores. To further improve the performance and scalability, FS-Join integrates horizontal partitioning. Experimental results on three real datasets show that FS-Join outperforms the state-of-theart methods by one order of magnitude on average, which demonstrates the good scalability and performance qualities of the proposed technique.

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
url_pdf: 'http://iir.ruc.edu.cn/~luwei/publications/icde2017.pdf'
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
