---
title: 'Fuzzing MLIR Compiler Infrastructure via Operation Dependency Analysis'
profile: false
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Chenyao Suo
  - Junjie Chen
  - Shuang Liu
  - Jiajun Jiang
  - Yingquan Zhao
  - Jianrong Wang
# Author notes (optional)

date: "2024-09-11T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2024-09-11T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['journal-conference']

# Publication name and optional abbreviated publication name.
publication: in *ISSTA*
publication_short: ""

abstract: MLIR (Multi-Level Intermediate Representation) compiler infrastructure has gained widespread popularity in recent years. It introduces dialects to accommodate various levels of abstraction within the representation. Due to its fundamental role in compiler construction, it is critical to ensure its correctness. Recently, a grammar-based fuzzing technique (i.e., MLIRSmith) has been proposed for it and achieves notable effectiveness. However, MLIRSmith generates test programs in a random manner, which restricts the exploration of the input space, thereby limiting the overall fuzzing effectiveness. In this work, we propose a novel fuzzing technique, called MLIR. As complicated or uncommon data/control dependencies among various operations are often helpful to trigger MLIR bugs, it constructs the operation dependency graph for an MLIR program and defines the associated operation dependency coverage to guide the fuzzing process. To drive the fuzzing process towards increasing operation dependency coverage, MLIR then designs a set of dependency-targeted mutation rules. By applying MLIR to the latest revisions of the MLIR compiler infrastructure, it detected 63 previously unknown bugs, among which 38/48 bugs have been fixed/confirmed by developers.

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/10.1145/3650212.3680360'
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
