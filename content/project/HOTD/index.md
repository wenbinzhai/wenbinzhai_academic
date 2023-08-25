---
title: HOTD
summary:  A holistic cross-layer time delay attack detection framework (HOTD) to detect time delay attack in UAV networks
tags:
  - Cybersecurity
  - Wireless Sensor Networks
date: '2022-01-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Main workflow of our framework (HOTD)
  focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
# url_code: ''
url_pdf: 'HOTD.pdf'
# url_slides: ''
# url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Proposed a **holistic cross-layer time delay attack detection framework (HOTD)** to detect time delay attack in UAV networks, which is easy to implement and difficult to detect. First, we perform a **holistic selection** of delay-related features at each layer of UAV networks. Then, supervised learning is used to construct a **consistency model** between these selected features and the corresponding forwarding delay, based on which the **consistent degree** of each node can be calculated. Finally, the K-Means clustering method is utilized to distinguish malicious nodes from benign ones according to their consistent degrees. (2021-2022, published in journal **Journal of Parallel and Distributed Computing (JPDC) [CORE A, CCF B, SCI-Q1, IF 4.542]**)