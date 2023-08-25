---
title: 'ETD: An Efficient Time Delay Attack Detection Framework for UAV Networks'

authors:
- admin
- Liang Liu
- Youwei Ding
- Shanshan Sun
- Ying Gu
author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: '2023-05-03'
doi: "10.1109/TIFS.2023.3272862"

# Schedule page publish date (NOT publication's date).
publishDate: '2023-05-03T07:05:47.654839Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Information Forensics and Security (**TIFS**)* [**CORE A**, CCF A, SCI-Q1, IF 7.231]'
publication_short: ""

abstract: In recent years, Unmanned Aerial Vehicle (UAV) networks are widely used in both military and civilian scenarios. However, due to the distributed nature, they are also vulnerable to threats from adversaries. Time delay attack is a type of internal attack which maliciously delays the transmission of data packets and further causes great damage to UAV networks. Furthermore, it is easy to implement and difficult to detect due to the avoidance of packet modification and the unique characteristics of UAV networks. However, to the best of our knowledge, there is no research on time delay attack detection in UAV networks. In this paper, we propose an Efficient Time Delay Attack Detection Framework (ETD). First, we collect and select delay-related features from four different dimensions, namely delay, node, message and connection. Meanwhile, we utilize the pre-planned trajectory information to accurately calculate the real forwarding delay of nodes. Then, one-class classification is used to train the detection model, and the forwarding behaviors of all nodes can be evaluated, based on which their trust values can be obtained. Finally, the K-Means clustering method is used to distinguish malicious nodes from benign ones according to their trust values. Through extensive simulation, we demonstrate that ETD can achieve higher than 80% detection accuracy with less than 2.5% extra overhead in various settings of UAV networks and different routing protocols.

# Summary. An optional shortened abstract.
summary: An Efficient Time Delay Attack Detection Framework to detect time delay attack in UAV networks, which is a less explored attack surface.

tags:
- Cybersecurity
- Wireless Sensor Networks
featured: true

# links:
# - name: ""
#   url: ""
# url_pdf: http://arxiv.org/pdf/1512.04133v1
url_pdf: "ETD.pdf"
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  caption: 'The overview of ETD'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}} -->

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->