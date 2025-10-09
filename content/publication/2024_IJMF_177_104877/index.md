---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Physics-aware recurrent convolutional neural networks for modeling multiphase compressible flows"
authors: ["**Cheng, Xinlun**", "Nguyen, Phong C.H.", "Seshadri, Pradeep K.", "Verma, Mayank", "Gray, Zoe J.", "Udaykumar, H.S.", "Baek, Stephen"]
date: 2024-07-01T00:00:00+00:00
doi: "10.1016/j.ijmultiphaseflow.2024.104877"
# Astronomy specific: NASA adsabs id

# Schedule page publish date (NOT publication's date).
publishDate: 2024-07-01T00:00:00+00:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "International Journal of Multiphase Flow (2024), 177, 104877"
publication_short: ""

abstract: ""
# Summary. An optional shortened abstract.
summary: ""

tags: ["Machine learning", "Artificial intelligence", "Physics-informed machine learning", "Fluid dynamics", "Data-driven modeling", "AI4Science"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://www.sciencedirect.com/science/article/pii/S030193222400154X/pdfft?md5=ff92eaff42909502185eb211e52010ca&pid=1-s2.0-S030193222400154X-main.pdf"
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
### Abstract
Multiphase compressible flow systems can exhibit unsteady and fast-transient dynamics, marked by sharp gradients and discontinuities, and material boundaries that interact with the evolving flow. The transient nature of the dynamics presents challenges to employing artificial intelligence (AI) and data-driven models for predicting flow behaviors. In this study, we explore the potential of physics-aware recurrent convolutional neural networks (PARC) to model the spatiotemporal dynamics of multiphase flows in the presence of shocks and reaction fronts. PARC is a neural network model that incorporates the generic form of the diffusion–advection–reaction equation in its network architecture, which mimics the process of solving the governing equations of fluid flows. In contrast to physics-informed machine learning approaches such as physics-informed neural networks (PINNs) where models are trained to directly minimize the residual of governing equations, PARC takes a dynamical systems viewpoint and does not seek to minimize potentially nonconvex and nonlinear loss terms. To assess the ability of PARC to accurately learn and simulate the physics of multiphase flows, we train and test PARC on various flow simulation problems, including the Burgers’ equation, fluid flow behind a cylindrical cross-section, and unsteady shock interactions with a particle at varying Mach numbers. We analyze PARC’s performance and examine sources of error in its prediction, in terms of differentiation and integration schemes and different weighting strategies for the model update. Based on our observations, we discuss PARC’s capabilities and limitations in multiphase flow applications and propose future research directions.
