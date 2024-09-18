---
title: 'A SQL-Based Solution for Fast Graph Similarity Search'
profile: false
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zhanhao Zhao
  - Feiran Huang
  - Xiaoli Wang
  - Wei Lu
  - Xiaoyong Du
# Author notes (optional)

# 论文发表时间, 格式为xxxx-xx-xxTxx:xx:xxZ, 需要完整填写，否则可能导致网站显示异常
date: "2018-02-01T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2018-02-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# 论文类型，会议为paper-conference，期刊为journal-article
publication_types: ['journal-article']

# Publication name and optional abbreviated publication name.
publication: In *软件学报*
publication_short: ""

# 文章摘要
abstract: 图作为一种表示复杂信息的数据结构,被广泛应用于社交网络、知识图谱、语义网、生物信息学和化学信息学等领域.随着各领域应用的普及和深入开展,如何管理这些复杂图数据,是目前图数据库技术面临的巨大挑战.图的相似性查询是图数据管理中的热点问题之一,对图查询问题的研究主要包括图的相似性查询等.重点研究基于编辑距离(graph  edit  distance)的图相似性查询处理问题.首先,通过对目前代表性的问题求解算法分析发现,目前已提出的过滤规则都具有自己的优缺点和适用性.其次,针对已有方法在过滤阶段自身存在的优缺点和适用性的问题,提出一种面向关系型数据库的过滤框架,新的过滤框架可以支持所有已有的过滤规则,从而通过结合不同的过滤规则来优化图相似查询算法以提高查询效率.该方法可以最大程度地保留不同过滤规则的优点并克服其缺点,从而对不同查询具有普遍适用性.最后,基于 PubChem 数据集,通过比较算法在求解查询结果的时间消耗,验证所提出算法的高效性及可扩展性.实验结果表明,所提出的方法优于现有算法.

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
url_pdf: 'http://gfiiz26f1a0fefa8a47b5s5xu0ww6p5uwq6obw.fcya.libproxy.ruc.edu.cn/record/display.uri?eid=2-s2.0-85049518938&origin=resultslist&sort=plf-f&src=s&nlo=&nlr=&nls=&sid=85cb8356dcca53f4e427e9ce736a88af&sot=a&sdt=a&sl=47&s=SRCTITLE%28Ruan+Jian+Xue+Bao%2fJournal+of+Software%29&relpos=585&citeCnt=0&searchTerm='
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
