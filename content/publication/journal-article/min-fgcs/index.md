---
title: "An efficient data collection algorithm for partitioned wireless sensor networks"
authors:
- Gongshun Min
- Liang Liu
- admin
- Zijie Wang
- Wanying Lu
author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2022-09-09T00:00:00Z"
doi: "https://doi.org/10.1016/j.future.2022.09.006"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-09-09T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Future Generation Computer Systems (**FGCS**)* [**CORE A**, CCF C, SCI-Q1, IF 7.307]"
publication_short: ""

abstract: Data collection with mobile agent (MA) can balance the energy consumption of nodes in partitioned wireless sensor networks. However, the existing data collection algorithms for partitioned WSNs do not formalize the problem systematically. These algorithms are not efficient and difficult to meet the timeliness requirement. In order to solve the above shortcomings, we first formalize the Data Collection Problem (DCP). Then, it is transformed into a Generalized Traveling Salesman Problem (GTSP), and we propose a GTSP-Based data collection Algorithm (GBA) to calculate the rendezvous points (RPs) and the moving path of MA. GBA selects RPs by solving the GTSP problem. Furthermore, based on GBA, we take advantage of constructing convex hull to plan a more efficient moving path for MA. In addition, in order to reduce the energy burden on the RPs, we design an Improved Shortest Path tree (ISP tree) to aggregate data from nodes to RPs in partitioned WSNs. Finally, extensive simulations demonstrate the effectiveness and advantages of our algorithm in terms of the length of MA’s moving path and the amount of data collection per unit time.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Routing Optimization
- Wireless Sensor Networks
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: "Min-FGCS.pdf"
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
