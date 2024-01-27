---
title: "Fast Semi-supervised Unmixing using Non-convex Optimization"

authors:
- B. Rasti
- admin
- J. Mairal
- J. Chanussot
date: "2024-01-21T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: "FUnmix"

abstract: "In this paper, we introduce a novel linear model tailored for semisupervised/library-based unmixing. Our model incorporates considerations for library mismatch while enabling the enforcement of the abundance sum-to-one constraint (ASC). Unlike conventional sparse unmixing methods, this model involves nonconvex optimization, presenting significant computational challenges. We demonstrate the efficacy of Alternating Methods of Multipliers (ADMM) in cyclically solving these intricate problems. We propose two semisupervised unmixing approaches, each relying on distinct priors applied to the new model in addition to the ASC: sparsity prior and convexity constraint. Our experimental results validate that enforcing the convexity constraint outperforms the sparsity prior for the endmember library. These results are corroborated across three simulated datasets (accounting for spectral variability and varying pixel purity levels) and the Cuprite dataset. Additionally, our comparison with conventional sparse unmixing methods showcases considerable advantages of our proposed model, which entails nonconvex optimization. Notably, our implementations of the proposed algorithms—fast semisupervised unmixing (FaSUn) and sparse unmixing using soft-shrinkage (SUnS)—prove considerably more efficient than traditional sparse unmixing methods. SUnS and FaSUn were implemented using PyTorch and provided in a dedicated Python package called Fast Semisupervised Unmixing (FUnmix), which is open-source and available at https://github.com/BehnoodRasti/FUnmix"
# Summary. An optional shortened abstract.
summary: "" 

featured: false

tags:
  - Hyperspectral
  - Unmixing
  - Sparse unmixing
  - Sparsity
  - GPU
  - Alternating direction method of multipliers
  - Non-convex optimization
  - PyTorch


links:
url_pdf: https://hal.science/hal-04409409v1/document
url_code: 'https://github.com/BehnoodRasti/FUnmix'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 

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
---
