---
title: 'FineStream: Fine-Grained Window-Based Stream Processing on CPU-GPU Integrated Architectures'
profile: false
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Feng Zhang
  - Lin Yang
  - Shuhao Zhang
  - Bingsheng He
  - Wei Lu
  - Xiaoyong Du
# Author notes (optional)

# 论文发表时间, 格式为xxxx-xx-xxTxx:xx:xxZ, 需要完整填写，否则可能导致网站显示异常
date: "2020-07-15T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2020-07-15T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# 论文类型，会议为paper-conference，期刊为journal-article
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *ATC*
publication_short: ""

# 文章摘要
abstract: Accelerating SQL queries on stream processing by utilizing heterogeneous coprocessors, such as GPUs, has shown to be an effective approach. Most works show that heterogeneous processors bring significant performance improvement because of their high parallelism and computation capacity. However, the discrete memory architectures with relatively low PCI-e bandwidth and high latency have dragged down the benefits of heterogeneous coprocessors. Recently, hardware vendors propose CPU-GPU integrated architectures that integrate CPU and GPU on the same chip. This integration provides new opportunities for fine-grained cooperation be-tween CPU and GPU for optimizing SQL queries on stream processing. In this paper, we propose a data stream system, called FineStream, for efficient window-based stream pro-cessing on integrated architectures. Particularly, FineStreamperforms fine-grained workload scheduling between CPU and GPU to take advantage of both architectures, and also targets at dynamic stream query co-processing with window handling. Our experimental results show that 1) on integrated architectures, FineStream achieves an average 52% throughput improvement and 36% lower latency over the state-of-the-art stream processing engine; 2) compared to the stream processing engine on the discrete architecture, FineStream on the integrated architecture achieves 10.4x price-throughput ratio, 1.8x energy efficiency, and can enjoy lower latency benefits.

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
url_pdf: 'https://www.usenix.org/system/files/atc20-zhang-feng.pdf'
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
