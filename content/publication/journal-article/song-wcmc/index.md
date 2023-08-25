---
title: "Path Planning for Multi-Vehicle-Assisted Multi-UAVs in Mobile Crowdsensing"
authors:
- Jiancheng Song
- Liang Liu
- Yulei Liu
- Jie Xi
- admin
author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2022-01-20T00:00:00Z"
doi: "https://doi.org/10.1155/2022/9778188"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-20T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Wireless Communications and Mobile Computing (**WCMC**)* [CCF C, SCI-Q3, IF 2.146]"
publication_short: ""

abstract: Due to the capability of fast deployment and controllable mobility, unmanned aerial vehicles (UAVs) play an important role in mobile crowdsensing (MCS). However, constrained by limited battery capacity, UAVs cannot serve a wide area. In response to this problem, the ground vehicle is introduced and used to transport, release, and recycle UAVs. However, existing works only consider a special scenario, one ground vehicle with multiple UAVs. In this paper, we consider a more general scenario, multiple ground vehicles with multiple UAVs. We formalize the multi-vehicle-assisted multi-UAV path planning problem, which is a joint route planning and task assignment problem (RPTSP). To solve RPTSP, an efficient multi-vehicle-assisted multi-UAV path planning algorithm (MVP) is proposed. In MVP, we first allocate the detecting points to proper parking spots and then propose an efficient heuristic allocation algorithm EHA to plan the paths of ground vehicles. Besides, a genetic algorithm and reinforcement learning are utilized to plan the paths of UAVs. MVP maximizes the profits of an MCS carrier with a response time constraint and minimizes the number of employed vehicles. Finally, performance evaluation demonstrates that MVP outperforms the baseline algorithm.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Wireless Sensor Networks
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: "Song-WCMC.pdf"
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
<!-- 
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->