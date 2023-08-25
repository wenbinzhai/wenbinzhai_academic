---
title: "Detection of packet dropping attack based on evidence fusion in IoT networks"
authors:
- Weichen Ding
- admin
- Liang Liu
- Ying Gu
- Hang Gao
author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2022-07-09T00:00:00Z"
doi: "doi.org/10.1155/2022/1028251"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-07-09T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Security and Communication Networks (**SCN**)* [CCF C, SCI-Q3, IF 1.968]"
publication_short: ""

abstract: Internet of Things (IoT) is widely used in environmental monitoring, smart healthcare, and other fields. Due to its distributed nature, IoT is vulnerable to various internal attacks. One of these attacks is the packet-dropping attack, which is very harmful. The existing packet-dropping attack detection algorithms are unsuitable for emerging resource-constrained IoT networks. For example, ML-based algorithms always inject numerous packets to obtain the training dataset. However, it is heavyweight for energy-limited nodes to forward these extra packets. In this paper, we propose a lightweight evidence fusion-based detection algorithm (EFDA), which leverages the packet forwarding evidence to identify malicious nodes. Firstly, EFDA finds the sequence numbers of dropped packets and their corresponding source nodes. Then, it traces the routing path of each dropped packet and collects evidence for detection. The evidence stored by nodes around the path record the node’s forwarding behaviors. Finally, the collected evidence is fused to evaluate the trust of nodes. Based on nodes’ trust, the K-means clustering is used to distinguish between malicious nodes and benign nodes. We conduct simulation experiments to compare EFDA with ML-based algorithms. The experimental results demonstrate that EFDA can detect the packet-dropping attack without injecting packets and achieve a higher detection accuracy.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Cybersecurity
- Wireless Sensor Networks
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: "Ding-SCN.pdf"
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
