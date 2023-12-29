---
title: 'Power-Aware Path Planning for Vehicle-Assisted Heterogeneous UAVs in Mobile Crowd Sensing'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Zixiao Zhou
- Liang Liu
- admin
- Jiancheng Song
- Yulei Liu

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2023-10-26T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-10-26T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2023 International Conference on Data, Information and Computing Science (**CDICS 2023**)*
# publication_short: In *ICW*

abstract: With the development of microelectronics in recent years, the performance of unmanned aerial vehicles (UAVs) has been improving continuously. Modern rotary-wing UAVs possess high maneuverability and agility, making them widely applied in mobile crowd sensing (MCS). In order to solve the shortcoming of limited battery capacity and expand the mission area of UAVs, the ground vehicle is introduced as a platform for transportation, launch, recycle, and recharging UAVs. However, existing studies only consider the case of vehicle-assisted homogeneous UAVs. In reality, due to different sensing requirements and UAV hardware, vehicles may need to assist heterogeneous UAVs with different sensors, flight speeds, and battery capacities. In this paper, we formalize and study the vehicle-assisted heterogeneous UAVs path planning problem, and decompose it into three sub-problems, namely detection point allocation, UAV path planning, and vehicle route planning. In order to solve the above problems, we proposes an efficient power-aware path planning algorithm for vehicle-assisted multi-heterogeneous-UAV (VHUPA). In VHUPA, we first design the genetic algorithm to find the allocation scheme of the detection points, then plan flight paths of UAVs at each parking spot according to the allocation scheme, and finally optimize the route of the ground vehicle according to the power consumption of UAVs to minimize the waiting time for charging. Performance evaluation demonstrates that time cost of the VHUPA solution is reduced by more than 21% compared with the existing algorithm.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Wireless Sensor Networks
- Plan Planning
# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'Zhou-CDICS.pdf'
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

