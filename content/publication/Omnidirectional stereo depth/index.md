---
title: 'Omnidirectional stereo depth estimation based on spherical deep network'
authors:
  - Ming Li
  - Xuejiao Hu
  - Jingzhao Dai
  - Yang Li
  - Sidan Du
  
  
#author_notes:
  
date: '2021-8-23T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-8-23T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *Image and Vision Computing *
#publication_short: In *CNIOT*

abstract: Omnidirectional depth estimation is an emerging research topic and has received significant attention in recent years. However, the existing methods were developed based on the theory of planar stereo matching; and introduce the nonlinear epipolar constraint and significant distortions of re-projections. In this paper, we propose a novel approach that use spherical CNNs and the epipolar constraint on sphere for omnidirectional depth estimation. We discuss the epipolar constraint for spherical stereo imaging and convert the nonlinear constraint on a planar projection to the linear constraint on a sphere. We then propose a Spherical Convolution Residual Network (SCRN) for omnidirectional depth estimation via the spherical linear epipolar constraint. The input equirectangular projection (ERP) images are sampled to spherical meshes and fed into SCRN to calculate spherical depth maps. For 2D visualization, we design a Planar Refinement Network (PRN) and adopt the cascade learning scheme to improve the accuracy of depth maps. This scheme reduces the errors caused by projection, interpolation, and the limitation of spherical representation. The experiment shows that our full scheme Cascade Spherical Depth Network (CSDNet) results in more accurate and detailed depth maps with lower errors, as compared to recent seminal works. Our approach yields the comparable performance to the other state-of-the-art works on the omnidirectional stereo datasets with less number of parameters. The effectiveness of the spherical network and the cascade learning scheme is validated, and the influence of spherical sampling density is also discussed.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Source Themes
featured: true

# 外部链接
url_pdf: 'https://doi.org/10.1016/j.imavis.2021.104264'
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
