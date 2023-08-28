---
title: "MAPP: An efficient multi-location task allocation framework with personalized
  location privacy-protecting in spatial crowdsourcing"
authors:
- Yu Fan
- Liang Liu
- Xingxing Zhang
- Huibin Shi
- admin
author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2023-01-01T00:00:00Z"
doi: "https://doi.org/10.1016/j.ins.2022.11.075"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Information Sciences (**IS**)*  [**CORE A**, CCF B, SCI-Q1, IF 8.233]"
publication_short: ""

abstract: Due to its wide coverage and strong scalability, spatial crowdsourcing (SC) has become a research hotspot in recent years. In order to assign tasks to closer workers, it is necessary for workers to provide accurate locations to the server. However, it will result in the leakage of the participants’ location privacy. Existing works provide each worker with the same level of location privacy protection, which cannot meet the different privacy requirements of various workers. In addition, most works assume that the tasks are single-location tasks, and do not consider multi-location tasks. In this paper, we propose the Multi-location Task Allocation Problem with personalized location privacy protection (MLTAP). As far as we know, we are the first to study MLTAP. We propose a Multi-location task Allocation framework with Personalized location Privacy-protecting (MAPP). In order to allocate tasks efficiently, we use the R-tree to store workers and minimum bounding rectangle to represent multi-location tasks, thus filtering the unreachable workers for tasks. To better eliminate the adverse effect of location confusion, the SC server sorts candidate workers by the ranking metrics and allocates multi-location tasks efficiently. Finally, we conduct experiments to verify that MAPP has good performance in terms of utility.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Privacy Protection
featured: false

# links:
# - name: ""
#   url: ""
# url_pdf: https://www.sciencedirect.com/science/article/pii/S0020025522013640
url_pdf: "Fan-IS.pdf"
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
