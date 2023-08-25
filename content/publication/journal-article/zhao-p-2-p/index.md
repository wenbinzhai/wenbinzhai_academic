---
title: "Efficient time-delay attack detection based on node pruning and model fusion"
authors:
- Wenjie Zhao
- Yu Wang
- admin
- Liang Liu
- Yulei Liu
author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2023-03-30T00:00:00Z"
doi: "https://doi.org/10.1007/s12083-023-01477-x"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-03-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Peer-to-Peer Networking and Applications (**PPNA**)* [CCF C, SCI-Q2, IF 3.488]"
publication_short: ""

abstract: IoT devices are vulnerable to various attacks because they are resource-limited. This paper introduces a novel type of attack called time-delay attack. The malicious nodes delay packet forwarding by extending the processing time of packets, thus affecting the performance and availability of the network. This attack is very stealthy and difficult to detect because it does not violate any communication protocol. To the best of our knowledge, how to detect the time-delay attack in IoT networks is still an open problem. We first propose a machine learning-based baseline algorithm to detect the time-delay attack. It models the system features of each node and the forwarding time of packets to detect whether a node is malicious or not. However, the baseline algorithm needs to detect all nodes in the network, which causes unnecessary resource consumption. Moreover, using a single model in the baseline algorithm does not have high robustness. To reduce the overhead and improve the detection performance, we design an efficient Detection algorithm based on Node pruning and Model fusion (DNM). DNM uses node pruning to filter out suspected nodes from all nodes. The suspected nodes are then detected according to a fusion model. We conduct experimental evaluations based on the Cooja network simulator. The experimental results show that baseline and DNM possess close to 90% accuracy, and DNM significantly outperforms other algorithms with an average F1-score of 0.85.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Cybersecurity
- Wireless Sensor Networks
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: "Zhao-P2P.pdf"
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
