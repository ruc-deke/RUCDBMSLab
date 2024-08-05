---
title: 'AeonG: An Efficient Built-in Temporal Support in Graph Databases'
profile: false
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - 侯佳敏
# Author notes (optional)

date: "2024-02-01T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2024-02-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *VLDB*
publication_short: ""

abstract: Real-world graphs are often dynamic and evolve over time. It is crucial for storing and querying a graph's evolution in graph databases. However, existing works either suffer from high storage overhead or lack efficient temporal query support, or both. In this paper, we propose AeonG, a new graph database with built-in temporal support. AeonG is based on a novel temporal graph model. To fit this model, we design a storage engine and a query engine. Our storage engine is hybrid, with one current storage to manage the most recent versions of graph objects, and another historical storage to manage the previous versions of graph objects. This separation makes the performance degradation of querying the most recent graph object versions as slight as possible. To reduce the historical storage overhead, we propose a novel anchor+delta strategy, in which we periodically create a complete version (namely anchor) of a graph object, and maintain every change (namely delta) between two adjacent anchors of the same object. To boost temporal query processing, we propose an anchor-based version retrieval technique in the query engine to skip unnecessary historical version traversals. Extensive experiments are conducted on both real and synthetic datasets. The results show that AeonG achieves up to 5.73× lower storage consumption and 2.57× lower temporal query latency against state-of-the-art approaches, while introducing only 9.74% performance degradation for supporting temporal features.

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2304.12212'
url_code: 'https://github.com/hououou/AeonG'

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
