---
title: 'Context-Aware Semantic Type Identification for Relational Attributes'
profile: false
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yue Ding
  - Yuhe Guo
  - Wei Lu
  - Haixiang Li
  - Meihui Zhang
  - Hui Li
  - Anqun Pan
  - Xiaoyong Du
# Author notes (optional)

date: "2023-07-01T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2023-07-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['journal-conference']

# Publication name and optional abbreviated publication name.
publication: in *JCST*
publication_short: ""

abstract:  Identifying semantic types for attributes in relations, known as attribute semantic type (AST) identification, plays an important role in many data analysis tasks, such as data cleaning, schema matching, and keyword search in databases. However, due to a lack of unified naming standards across prevalent information systems (a.k.a. information islands), AST identification still remains as an open problem. To tackle this problem, we propose a context-aware method to figure out the ASTs for relations in this paper. We transform the AST identification into a multi-class classification problem and propose a schema context aware (SCA) model to learn the representation from a collection of relations associated with attribute values and schema context. Based on the learned representation, we predict the AST for a given attribute from an underlying relation, wherein the predicted AST is mapped to one of the labeled ASTs. To improve the performance for AST identification, especially for the case that the predicted semantic types of attributes are not included in the labeled ASTs, we then introduce knowledge base embeddings (a.k.a. KBVec) to enhance the above representation and construct a schema context aware model with knowledge base enhanced (SCA-KB) to get a stable and robust model. Extensive experiments based on real datasets demonstrate that our context-aware method outperforms the state-of-the-art approaches by a large margin, up to 6.14% and 25.17% in terms of macro average score, and up to 0.28% and 9.56% in terms of weighted score over high-quality and low-quality datasets respectively.

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://link.springer.com/article/10.1007/s11390-021-1048-y'
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
