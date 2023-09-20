---
title: "ESTA: An Efficient Spatial-Temporal Range Aggregation Query Processing Algorithm for UAV Networks"
authors:
- admin
- Xin Li
- Liang Liu
- Youwei Ding
- Wanying Lu
date: '2023-08-23T00:00:00Z'
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: '2023-08-23T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Arxiv"
publication_short: ""

abstract: Unmanned Aerial Vehicle (UAV) networks have been widely used in both military and civilian scenarios. When users are interested in the statistical information of the historical sensory data in a certain region during a certain time period, they will send an aggregation query request with a spatial-temporal constraint to target UAVs which store the qualified data. Then, the target UAVs will return the query results to users. Meanwhile, the query results can be aggregated within the network during transmission to save energy and bandwidth resources, which are typically scarce in UAV networks. However, due to the unique characteristics of UAV networks, it is difficult to perform efficient in-network aggregation of query results without the sacrifice of the user query delay. To the best of our knowledge, there is no research on spatial-temporal range aggregation query in UAV networks. In this paper, we propose an Efficient Spatial-Temporal range Aggregation query processing (ESTA) algorithm for UAV networks. First, a topology change graph is constructed based on the pre-planned trajectory information. Meanwhile, an efficient shortest path algorithm is proposed to obtain the user query delay. Then, on the basis of ensuring the user query delay, ESTA transforms the aggregation processing of query results into recursively solving the set cover problem, thereby constructing a spatial-temporal aggregation tree (STAT), based on which an efficient in-network aggregation routing path for query results can be found. Through extensive simulation, we demonstrate that ESTA can save more than 50% of the energy consumption compared with the baseline algorithm.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
# - Cybersecurity
- Wireless Sensor Networks
- Routing Optimization
featured: false

links:
- name: Arxiv
  url: https://arxiv.org/abs/2308.11977
url_pdf: "ESTA.pdf"
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
