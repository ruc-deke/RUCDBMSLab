---
title: 'Efficient Model Store and Reuse in an OLML Database System'
profile: false
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Jianwei Cui
  - Wei Lu
  - Xin Zhao
  - Xiaoyong Du
# Author notes (optional)

date: "2021-07-30T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2021-07-30T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['journal-article']

# Publication name and optional abbreviated publication name.
publication: in *JCST*
publication_short: ""

abstract: Deep learning has shown significant improvements on various machine learning tasks by introducing a wide spectrum of neural network models. Yet, for these neural network models, it is necessary to label a tremendous amount of training data, which is prohibitively expensive in reality. In this paper, we propose OnLine Machine Learning (OLML) database which stores trained models and reuses these models in a new training task to achieve a better training effect with a small amount of training data. An efficient model reuse algorithm AdaReuse is developed in the OLML database. Specifically, AdaReuse firstly estimates the reuse potential of trained models from domain relatedness and model quality, through which a group of trained models with high reuse potential for the training task could be selected efficiently. Then,multi selected models will be trained iteratively to encourage diverse models, with which a better training effect could be achieved by ensemble. We evaluate AdaReuse on two types of natural language processing (NLP) tasks, and the results show AdaReuse could improve the training effect significantly compared with models training from scratch when the training data is limited. Based on AdaReuse, we implement an OLML database prototype system which could accept a training task as an SQL-like query and automatically generate a training plan by selecting and reusing trained models. Usability studies are conducted to illustrate the OLML database could properly store the trained models, and reuse the trained models efficiently in new training tasks.

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://jcst.ict.ac.cn/fileup/1000-9000/PDF/2021-4-6-1353.pdf'

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
