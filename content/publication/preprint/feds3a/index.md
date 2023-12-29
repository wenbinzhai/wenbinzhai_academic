---
title: "Federated Semi-Supervised and Semi-Asynchronous Learning for Anomaly Detection in IoT Networks"
authors:
- admin
- Feng Wang
- Liang Liu
- Youwei Ding
- Wanying Lu
date: '2023-08-23T01:00:00Z'
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: '2023-08-23T01:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "*Arxiv*"
publication_short: ""

abstract: Existing FL-based approaches are based on the unrealistic assumption that the data on the client-side is fully annotated with ground truths. Furthermore, it is a great challenge how to improve the training efficiency while ensuring the detection accuracy in the highly heterogeneous and resource-constrained IoT networks. Meanwhile, the communication cost between clients and the server is also a problem that can not be ignored. Therefore, in this paper, we propose a Federated Semi-Supervised and Semi-Asynchronous (FedS3A) learning for anomaly detection in IoT networks. First, we consider a more realistic assumption that labeled data is only available at the server, and pseudo-labeling is utilized to implement federated semi-supervised learning, in which a dynamic weight of supervised learning is exploited to balance the supervised learning at the server and unsupervised learning at clients. Then, we propose a semi-asynchronous model update and staleness tolerant distribution scheme to achieve a trade-off between the round efficiency and detection accuracy. Meanwhile, the staleness of local models and the participation frequency of clients are considered to adjust their contributions to the global model. In addition, a group-based aggregation function is proposed to deal with the non-IID distribution of the data. Finally, the difference transmission based on the sparse matrix is adopted to reduce the communication cost. Extensive experimental results show that FedS3A can achieve greater than 98% accuracy even when the data is non-IID and is superior to the classic FL-based algorithms in terms of both detection performance and round efficiency, achieving a win-win situation. Meanwhile, FedS3A successfully reduces the communication cost by higher than 50%.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Cybersecurity
- Wireless Sensor Networks
# - Routing Optimization
featured: false

links:
- name: Arxiv
  url: https://arxiv.org/abs/2308.11981
url_pdf: "FedS3A.pdf"
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: "PostgraduateThesisSlides.pptx"
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - Cybersecurity
# - Wireless Sensor Networks
# - Routing Optimization

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
