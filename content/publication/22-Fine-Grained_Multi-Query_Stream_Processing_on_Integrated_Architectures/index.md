---
title: 'Fine-Grained Multi-Query Stream Processing on Integrated Architectures'
profile: false
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Feng Zhang
  - Chenyang Zhang
  - Lin Yang
  - Shuhao Zhang
  - Bingsheng He
  - Wei Lu 
  - Xiaoyong Du
# Author notes (optional)

# 论文发表时间, 格式为xxxx-xx-xxTxx:xx:xxZ, 需要完整填写，否则可能导致网站显示异常
date: "2021-05-17T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2021-05-17T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# 论文类型，会议为paper-conference，期刊为journal-article
publication_types: ['journal-article']

# Publication name and optional abbreviated publication name.
publication: In *TPDS*
publication_short: ""

# 文章摘要
abstract: Exploring the sharing opportunities among multiple stream queries is crucial for high-performance stream processing. Modern stream processing necessitates accelerating multiple queries by utilizing heterogeneous coprocessors, such as GPUs, and this has shown to be an effective method. Emerging CPU-GPU integrated architectures 6integrate CPU and GPU on the same chip and eliminate PCI-e bandwidth bottleneck. Such a novel architecture provides new opportunities for improving multi-query performance in stream processing but has not been fully explored by existing systems. We introduce a stream processing engine, called FineStream, for efficient multi-query window-based stream processing on CPU-GPU integrated architectures. FineStream's key contribution is a novel fine-grained workload scheduling mechanism between CPU and GPU to take advantage of both architectures. Particularly, FineStream is able to efficiently handle multiple queries in both static and dynamic streams. Our experimental results show that 1) on integrated architectures, FineStream achieves an average 52 percent throughput improvement and 36 percent lower latency over the state-of-the-art stream processing engine; 2) compared to the coarse-grained strategy of applying different devices for multiple queries, FineStream achieves 32 percent throughput improvement; 3) compared to the stream processing engine on the discrete architecture, FineStream on the integrated architecture achieves 10.4× price-throughput ratio, 1.8× energy efficiency, and can enjoy lower latency benefits.

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
url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9380479'
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
