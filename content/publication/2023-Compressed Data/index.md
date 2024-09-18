---
title: 'Compressed Data Direct Computing for Databases'
profile: false
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Weitao Wan
  - Feng Zhang
  - Chenyang Zhang
  - Mingde Zhang
  - Jidong Zhai
  - Yunpeng Chai
  - Huanchen Zhang
  - Wei Lu
  - Yuxing Chen
  - Haixiang Li
  - Anqun Pan
  - Xiaoyong Du
# Author notes (optional)

date: "2023-09-18T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-18T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['journal-conference']

# Publication name and optional abbreviated publication name.
publication: in *TKDE*
publication_short: ""

abstract: Directly performing operations on compressed data has been proven to be a big success facing Big Data problems in modern data management systems. These systems have demonstrated significant compression benefits and performance improvement for data analytics applications. However, current systems only focus on data queries, while a complete Big Data system must support both data query and data manipulation. To solve this problem, we develop CompressDB, which is a new storage engine that can support data processing for databases without decompression. CompressDB has the following advantages. First, CompressDB utilizes context-free grammar to compress data, and supports both data query and data manipulation. Second, for adaptability, we integrate CompressDB to file systems so that a wide range of databases can directly use CompressDB without any change. Third, we enable operation pushdown to storage so that we can perform data query and manipulation in storage systems without bringing large data to memory for high efficiency. We validate the efficacy of CompressDB supporting various kinds of database systems, including SQLite, MySQL, LevelDB, MongoDB, ClickHouse, and Neo4j. We evaluate our method using seven real-world datasets with various lengths, structures, and content in both single node and cluster environments. Experiments show that CompressDB achieves 40% throughput improvement and 44% latency reduction, along with 1.75 compression ratio on average.

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10254348'
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
