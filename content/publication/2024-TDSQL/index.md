---
title: 'TDSQL: Tencent Distributed Database System'
profile: false
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yuxing Chen
  - Anqun Pan
  - Hailin Lei
  - Anda Ye
  - Shuo Han
  - Yan Tang
  - Wei Lu
  - Yunpeng Chai
  - Feng Zhang
  - Xiaoyong Du
# Author notes (optional)

date: "2024-08-01T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2024-08-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['journal-conference']

# Publication name and optional abbreviated publication name.
publication: in *PVLDB*
publication_short: ""

abstract:  Distributed databases have become indispensable in contemporary computing and data processing, owing to their pivotal role in ensuring high availability and scalability. They effectively cater to the requirements of data management and high-concurrency access. However, developing a distributed database system that is well-suited for diverse application scenarios, particularly for large-scale applications, presents several challenges. These challenges include ensuring data consistency and achieving high levels of performance. This paper presents TDSQL, a distributed database system that prioritizes core design principles of distributed systems, including high availability, strong consistency, and scalability. In particular, TDSQL has achieved high performance through over a decade of practical experience and optimization in various modules, such as the kernel, synchronous replication, and transaction processing, in large-scale application scenarios. By conducting the TPC-C benchmark test, TDSQL demonstrated outstanding performance, achieving a throughput of 814 million tpmC across 1650 database nodes, with a jitter rate of less than 0.2%. This jitter rate is an order of magnitude lower than the standard required, showcasing the system's stability and reliability. During the 8-hour TPC-C standard stress test, TDSQL successfully completed over 860 billion transactions and processed 40 trillion order details, with zero forced rollbacks and zero data inconsistency

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.vldb.org/pvldb/vol17/p3869-chen.pdf'
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
