---
title: 'VeriTxn: Verifiable Transactions for Cloud-Native Databases with Storage Disaggregation'
profile: false
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zhanhao Zhao
  - Hexiang Pan
  - Gang Chen
  - Xiaoyong Du
  - Wei Lu
  - Beng Chin Ool
# Author notes (optional)

date: "2023-11-12T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2023-11-12T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['journal-conference']

# Publication name and optional abbreviated publication name.
publication: in *SIGMOD*
publication_short: ""

abstract:  Cloud-native databases become increasingly popular while exposing to greater data security and correctness risks. Existing verifiable outsourced databases overlook either the correctness risk of transactions, or the disaggregation architecture: a key design consideration of cloud-native databases for performance and elasticity, or both. We present VeriTxn, a novel cloud-native database that efficiently provides verifiability of transaction correctness. VeriTxn relies on the trusted hardware (i.e., Intel SGX) to enable verifiable transaction processing. We build a page-structure cache in the trusted domain, where transactions can be verified with low, constant overhead. VeriTxn further optimizes the read-only transactions by exploiting disaggregation to fit the read-heavy workload in the cloud. We also integrate our proposal into MySQL, a popular open-source database. We conduct extensive experiments to compare VeriTxn against state-of-the-art verifiable databases and evaluate the performance of VeriTxn on MySQL. The results show that VeriTxn introduces tolerable performance degradation for verifiable transactions, while achieving up to 7.03× and 7.93× higher throughput than Litmus and LedgerDB, and its sustainable performance when integrated with MySQL.

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/10.1145/3626764'
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
