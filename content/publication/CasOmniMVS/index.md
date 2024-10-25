---
title: 'CasOmniMVS: Cascade Omnidirectional Depth Estimation with Dynamic Spherical Sweeping'
authors:
  - Pinzhi Wang
  - Ming Li
  - Jinghao Cao
  - Sidan Du
  - Yang Li
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
date: '2024-01-06T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-06T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *Applied Sciences*
#publication_short: In *ECCV*

abstract: Estimating 360° depth from multiple cameras has been a challenging problem. However, existing methods often adopt a fixed-step spherical sweeping approach with densely sampled spheres and use numerous 3D convolutions in networks, which limits the speed of algorithms in practice. Additionally, obtaining high-precision depth maps of real scenes poses a challenge for the existing algorithms. In this paper, we design a cascade architecture using a dynamic spherical sweeping method that progressively refines the depth estimation from coarse to fine over multiple stages. The proposed method adaptively adjusts sweeping intervals and ranges based on the predicted depth and the uncertainty from the previous stage, resulting in a more efficient cost aggregation performance. The experimental results demonstrated that our method achieved state-of-the-art accuracy with reduced GPU memory usage and time consumption compared to the other methods. Furthermore, we illustrate that our method achieved satisfactory performance on real-world data, despite being trained on synthetic data, indicating its generalization potential and practical applicability.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Source Themes
featured: true

# 外部链接
url_pdf: 'https://www.mdpi.com/2076-3417/14/2/517/pdf'
#url_code: 'https://github.com/nju-ee/MODE-2022'
#url_dataset: '#'
#url_poster: '#'
#url_video: 'https://www.youtube.com/watch?v=Fw-KR35UWgQ'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
