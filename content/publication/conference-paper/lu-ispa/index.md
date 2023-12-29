---
title: 'HBC: Combining Lossy and Lossless Hybrid Bilayer Compression Framework on Time-Series Data'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Wanying Lu
- Liang Liu
- admin
- Haoyuan Chen
- Yulei Liu

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2023-10-18T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-10-18T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *the 21th IEEE International Symposium on Parallel and Distributed Processing with Applications (**ISPA 2023**)* [CCF C]
# publication_short: In *ICW*

abstract:  The popularization and application of the Internet of Things (IoT) technology has brought massive time series data, which puts forward higher requirements for data compression technology. At present, most existing compression methods use only a single lossy or lossless compression algorithm to perform data compression. Furthermore, traditional lossy compression methods usually adopt a fixed error threshold. However, in practical applications, users have different accuracy requirements for time series data in different numerical ranges. In this paper, we design a Hybrid Bilayer Compression (HBC) framework, which consists of a data accuracy-aware lossy compression layer and a data feature-aware lossless compression layer. First, the original time series data is lossy compressed on the top layer of HBC, where the error threshold can be adaptively adjusted according to the user's accuracy requirements. Then, based on the features of lossy compressed data, we use supervised learning to select the optimal lossless compression algorithm from the algorithm pool to further compress the data. Experimental results show that compared with three state-of-the-art compression algorithms, HBC reduces the storage space by 52.1%, 91.66%, and 92.27%, respectively.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Databases

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'Lu-ISPA.pdf'
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_poster: 'Lu_ISPA_Poster.pdf'
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

