---
title: '面向列语义识别的共现属性交互模型构建与优化'
profile: false
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - 高珊
  - 袁宛竹
  - 卢卫
  - 王兰
  - 张静
  - 杜小勇
# Author notes (optional)

date: "2023-03-01T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2023-03-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['journal-conference']

# Publication name and optional abbreviated publication name.
publication: in *软件学报*
publication_short: ""

abstract: 政务数据治理正在经历从“物理数据汇聚”到“逻辑语义汇通”的新阶段. 逻辑语义汇通是指针对各孤岛政务系统因长期“自治”而形成的元数据缺失、元数据同名不同义以及同义不同名等问题, 在不重建或修改原系统代码以及不物理汇聚各政务数据的前提下, 通过技术手段, 统一各孤岛信息系统元数据的语义表达, 实现元数据的语义互联互通. 该工作是将各孤岛信息系统的元数据语义对齐到已有的标准元数据上, 具体地, 将标准元数据名称看作语义标签, 对孤岛关系数据的列投影进行语义识别, 从而建立列名和标准元数据的语义对齐, 实现孤岛元数据标准化治理. 已有基于列投影的语义识别技术无法捕捉到关系数据的列顺序无关性特征以及属性语义标签之间的相关性特征, 针对这一问题, 提出了基于预测阶段和纠错阶段的两阶段模型:在预测阶段, 提出了共现属性交互的 CAI 模型(co-occurrence-attribute-interaction model), 利用并行化的自注意力机制保证列顺序无关的共现属性交互; 在纠错阶段, 结合语义标签之间的共现性, 通过引入纠错机制(correction mechanism), 优化 CAI 模型预测结果. 在政务基准数据和 Magellan 等多组公开英文数据集上进行了实验, 结果表明, 引入纠错机制的两阶段模型,在宏平均和加权平均两个指标上, 比已有最优模型最多可分别提高 20.03%, 13.36%.

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.jos.org.cn/jos/article/abstract/6787'
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
