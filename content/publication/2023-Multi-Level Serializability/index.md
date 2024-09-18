---
title: 'Efficiently Supporting Multi-Level Serializability in Decentralized Database Systems'
profile: false
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zhanhao Zhao
  - Hongyao Zhao
  - Qiyu Zhuang
  - Wei Lu
  - Haixiang Li
  - Meihui Zhang
  - Anqun Pan
  - Xiaoyong Du
# Author notes (optional)

date: "2023-05-19T00:00:00Z"
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2023-05-19T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['journal-conference']

# Publication name and optional abbreviated publication name.
publication: in *TKDE*
publication_short: ""

abstract:  In decentralized database systems, it is reported that serializability could still produce unexpected transaction orderings, leading to the stale read anomaly. To eliminate this anomaly, strict serializability imposes an additional ordering constraint, called the real-time order, which is required to be preserved among serializable transactions. Yet, preserving the real-time order in strict serializability often causes the performance to drop significantly. Because a weaker data consistency often yields better performance, in this paper, we model serializability from different consistency perspectives to properly leverage the performance and consistency. To do this, we first define a group of orderings, based on which we formulate multi-level serializability by preserving a certain set of ordering constraints among transactions. We then propose a bidirectional timestamp adjustment algorithm (abbreviated as BDTA) to support multi-level serializability with various optimizations. Our special design makes ordering constraints among transactions be preserved simply by adjusting timestamp intervals. Finally, we conduct extensive experiments to show the necessity of introducing multi-level serializability and confirm that BDTA achieves up to 1.19 × better performance than the state-of-the-art concurrency control algorithms.

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10129870'
url_code: 'https://github.com/dbiir/BDTA'

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
