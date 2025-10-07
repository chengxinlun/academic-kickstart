---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Convolutional neural networks for large-scale dynamical modeling of itinerant magnets"
authors: ["Cheng, Xinlun",  "Zhang, Sheng", "Nguyen, Phong C.H.", "Azarfar, Shahab", "Chern, Gia-Wei", "Baek, Stephen"]
date: 2023-09-01T00:00:00+00:00
doi: "10.1103/PhysRevResearch.5.033188"
arxiv: "2306.11833"
# Astronomy specific: NASA adsabs id

# Schedule page publish date (NOT publication's date).
publishDate: 2023-03-01T00:00:00+00:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Physics Review Research"
publication_short: ""

abstract: "Complex spin textures in itinerant electron magnets hold promises for next-generation memory and information technology. The long-ranged and often frustrated electron-mediated spin interactions in these materials give rise to intriguing localized spin structures such as skyrmions. Yet, simulations of magnetization dynamics for such itinerant magnets are computationally difficult due to the need for repeated solutions to the electronic structure problems. We present a convolutional neural network (CNN) model to accurately and efficiently predict the electron-induced magnetic torques acting on local spins. Importantly, as the convolutional operations with a fixed kernel (receptive field) size naturally take advantage of the locality principle for many-electron systems, CNNs offer a scalable machine learning approach to spin dynamics. We apply our approach to enable large-scale dynamical simulations of skyrmion phases in itinerant spin systems. By incorporating the CNN model into Landau-Lifshitz-Gilbert dynamics, our simulations successfully reproduce the relaxation process of the skyrmion phase and stabilize a skyrmion lattice in larger systems. The CNN model also allows us to compute the effective receptive fields, thus providing a systematic and unbiased method for determining the locality of the original electron models."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Machine Learning", "Artificial Intelligence", "Spin Dynamics"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code:
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
