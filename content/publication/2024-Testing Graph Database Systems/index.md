---
title: 'Testing Graph Database Systems with Graph-State Persistence Oracle'
profile: false
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Shuang Liu
  - Junhao Lan
  - Xiaoning Du
  - Jiyuan Li
  - Wei Lu
  - Jiajun Jiang
  - Xiaoyong Du
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

abstract:  Graph Database Management Systems (GDBMSs) store data in a graph format, facilitating rapid querying of nodes and relationships. This structure is particularly advantageous for applications like social networks and recommendation systems, which often involve frequent writing operations—such as adding new nodes, creating relationships, or modifying existing data—that potentially introduce bugs. However, existing GDBMS testing approaches tend to overlook these writing functionalities, failing to detect bugs arising from such operations. In this paper we present GraspDB, the first metamorphic testing approach specifically designed to identify bugs related to writing operations in graph database systems. GraspDB employs the Graph-State Persistence oracle, which is based on the Labeled Property Graph Isomorphism (LPG-Isomorphism) and Labeled Property Subgraph Isomorphism (LPSG-Isomorphism) relations. We also develop three classes of mutation rules aimed at engaging more diverse writing-related code logic. GraspDB has successfully detected 77 unique, previously unknown bugs across four popular open source graph database engines, among which 58 bugs are confirmed by developers, 43 bugs have been fixed and 31 are related to writing operations.

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/10.1145/3650212.3680311'
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
