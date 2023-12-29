---
title: 'EKR: An Efficient K-anycast Routing in UAV Networks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Kun Guo
- Liang Liu
- admin
- Youwei Ding

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2023-11-14T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-11-14T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *the 9th International Conference on Computer and Communications (**ICCC 2023**)*
# publication_short: In *ICW*

abstract: K-anycast refers to a communication model where a message is transmitted from a source to k destinations. Compared to multicast and unicast, k-anycast offers significant advantages in terms of load balancing, redundancy, and improved reliability. As far as we know, there is currently no research on k-anycast for UAV networks. We propose an Efficient K-anycast Routing scheme called EKR. The high dynamism of UAV networks poses a challenge in formalizing and addressing the k-anycast problem. Therefore, this paper utilizes predetermined trajectory information to construct Encounter Record Tree (ER-Tree), which converts dynamically changing network topologies into a static graph. Based on ER-Tree, we formalize the k-anycast problem in UAV networks and transform it into a Group Steiner Tree problem, which is known to be NP-hard. Then an efficient search algorithm is proposed to solve it and find the transmission path. To evaluate the performance of EKR, we performed simulations with the One simulator. The results demonstrate that EKR outperforms existing protocols in terms of delivery rate, end-to-end delay, and network overhead.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Wireless Sensor Networks
- Routing Optimization
# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'Guo-ICCC.pdf'
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: ''
# url_project: ''
url_slides: ''
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
  # - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->

