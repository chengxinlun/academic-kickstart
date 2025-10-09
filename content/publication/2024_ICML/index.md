---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "PARCv2: Physics-aware Recurrent Convolutional Neural Networks for Spatiotemporal Dynamics Modeling"
authors: ["Nguyen, Phong C.H.", "**Cheng, Xinlun**", "Azarfar, Shahab", "Seshadri, Pradeep", "Nguyen, Yen T.", "Kim, Munho", "Choi, Sanghun", "Udaykumar, H.S.", "Baek, Stephen"]
date: 2024-07-01T00:00:00+00:00
arxiv: "2402.12503"
# Astronomy specific: NASA adsabs id

# Schedule page publish date (NOT publication's date).
publishDate: 2024-07-01T00:00:00+00:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 41st International Conference on Machine Learning (PMLR, 2024), 235, 37649"
publication_short: ""

abstract: ""
# Summary. An optional shortened abstract.
summary: ""

tags: ["Machine learning", "Artificial intelligence", "Physics-informed machine learning", "Fluid dynamics", "Reactive flow", "AI4Science"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://proceedings.mlr.press/v235/nguyen24c.html"
url_code: "https://github.com/hphong1990/PARCv2"
url_dataset:
url_poster: "https://icml.cc/media/PosterPDFs/ICML%202024/33980.png?t=1719323622.7335463"
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
### Abstract
Modeling unsteady, fast transient, and advection-dominated physics problems is a pressing challenge for physics-aware deep learning (PADL). The physics of complex systems is governed by large systems of partial differential equations (PDEs) and ancillary constitutive models with nonlinear structures, as well as evolving state fields exhibiting sharp gradients and rapidly deforming material interfaces. Here, we investigate an inductive bias approach that is versatile and generalizable to model generic nonlinear field evolution problems. Our study focuses on the recent physics-aware recurrent convolutions (PARC), which incorporates a differentiator-integrator architecture that inductively models the spatiotemporal dynamics of generic physical systems. We extend the capabilities of PARC to simulate unsteady, transient, and advection-dominant systems. The extended model, referred to as PARCv2, is equipped with differential operators to model advection-reaction-diffusion equations, as well as a hybrid integral solver for stable, long-time predictions. PARCv2 is tested on both standard benchmark problems in fluid dynamics, namely Burgers and Navier-Stokes equations, and then applied to more complex shock-induced reaction problems in energetic materials. We evaluate the behavior of PARCv2 in comparison to other physics-informed and learning bias models and demonstrate its potential to model unsteady and advection-dominant dynamics regimes.
