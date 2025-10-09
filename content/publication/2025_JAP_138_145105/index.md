---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Physics-Aware Deep Learning Model for Shear Band Formation Around Collapsing Pores in Shocked Reactive Materials"
authors: ["**Cheng, Xinlun**", "Chen, Bingzhe", "Choi, Joseph B.", "Nguyen, Yen T.", "Seshadri, Pradeep", "Verma, Mayank", "Udaykumar, H.S.", "Baek, Stephen"]
date: 2025-10-01T00:00:00+00:00
doi: "10.1063/5.0294397"
# Astronomy specific: NASA adsabs id

# Schedule page publish date (NOT publication's date).
publishDate: 2025-10-01T00:00:00+00:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Journal of Applied Physics (2025), 138, 145105"
publication_short: ""

abstract: ""
# Summary. An optional shortened abstract.
summary: ""

tags: ["Machine learning", "Artificial intelligence", "Physics-informed machine learning", "Reactive material", "Shear bands", "Data-driven modeling", "AI4Science"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://pubs.aip.org/aip/jap/article-pdf/doi/10.1063/5.0294397/20740227/145105_1_5.0294397.pdf"
url_code: "https://github.com/chengxinlun/shear_bands"
url_dataset:
url_poster:
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
Modeling shock-to-detonation phenomena in energetic materials (EMs) requires capturing complex physical processes such as strong shocks, rapid changes in microstructural morphology, and nonlinear dynamics of chemical reaction fronts. These processes participate in energy localization at hotspots, which initiate chemical energy release leading to detonation. This study addresses the formation of hotspots in crystalline EMs subjected to weak-to-moderate shock loading, which, despite its critical relevance to the safe storage and handling of EMs, remains underexplored compared to the well-studied strong shock conditions. To overcome the computational challenges associated with direct numerical simulations, we advance the Physics-Aware Recurrent Convolutional Neural Network (PARCv2), which has been shown to be capable of predicting strong shock responses in EMs. We improved the architecture of PARCv2 to rapidly predict shear localizations and plastic heating, which play important roles in the weak-to-moderate shock regime. PARCv2 is benchmarked against two widely used physics-informed models, namely, Fourier neural operator and neural ordinary differential equation; we demonstrate its superior performance in capturing the spatiotemporal dynamics of shear band formation. While all models exhibit certain failure modes, our findings underscore the importance of domain-specific considerations in developing robust AI-accelerated simulation tools for reactive materials.
