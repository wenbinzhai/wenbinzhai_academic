---
title: 'OSIS: Obstacle-Sensitive and Initial-Solution-First Path Planning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Kaibin Zhang
- Liang Liu
- admin
- Youwei Ding
- Jun Hu

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2023-10-28T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-10-28T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *the 29th IEEE International Conference on Parallel and Distributed Systems (**ICPADS 2023**)* [CCF C]
# publication_short: In *ICW*

abstract: Informed path planning is a type of algorithm that uses problem-specific knowledge, expressed as heuristics, to efficiently discover an optimal path between a start and goal state. The efficiency of an informed algorithm is contingent upon how quickly the planner can find the initial solution and the associated overhead involved in collision detection. Existing informed planners do not fully exploit the information contained in historical collision detection results, resulting in additional unnecessary collision detections. Furthermore, they optimize paths through rewiring before discovering an initial solution. This approach not only hampers the planner’s space exploration, but also generates a superfluous amount of unproductive overhead. In this paper, an Obstacle-Sensitive and Initial-Solution-first path planning algorithm (OSIS) is proposed. OSIS leverages historical collision detection results to construct an asymptotically accurate distribution of obstacles in space. Based on this distribution, OSIS employs a reusable, inadmissible yet more accurate heuristic that applies to the entire problem domain. Additionally, an initial-solution-first path optimization strategy is proposed to eliminate unnecessary path optimization. It ensures that OSIS prioritizes exploring uncharted spaces, leading to faster initial solution discovery. Experiments have demonstrated that OSIS outperforms existing algorithms in navigating around obstacles, and achieving convergence in solution cost.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Path Planning
- Wireless Sensor Networks

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'Zhang-ICPADS.pdf'
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

