---
title: "SUnAA: Sparse Unmixing Using Archetypal Analysis"
authors:
- B. Rasti
- admin
- J. Mairal
- J. Chanussot
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2023-06-08T00:00:00Z"
doi: "10.1109/LGRS.2023.3284221"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Geoscience and Remote Sensing Letters"
publication_short: "GRSL"

abstract: "This letter introduces a new sparse unmixing technique using archetypal analysis (SUnAA). First, we design a new model based on archetypal analysis (AA). We assume that the endmembers of interest are a convex combination of endmembers provided by a spectral library and that the number of endmembers of interest is known. Then, we propose a minimization problem. Unlike most conventional sparse unmixing methods, here the minimization problem is nonconvex. We minimize the optimization objective iteratively using an active set algorithm. Our method is robust to the initialization and only requires the number of endmembers of interest. SUnAA is evaluated using two simulated datasets for which results confirm its better performance over other conventional and advanced techniques in terms of signal-to-reconstruction error (SRE). SUnAA is also applied to Cuprite dataset and the results are compared visually with the available geological map provided for this dataset. The qualitative assessment demonstrates the successful estimation of the minerals abundances and significantly improves the detection of dominant minerals compared to the conventional regression-based sparse unmixing methods. The Python implementation of SUnAA can be found at: https://github.com/BehnoodRasti/SUnAA ."
# Summary. An optional shortened abstract.
summary: ""
tags:
- active-set algorithm
- archetypal analysis
- hyperspectral imaging
- semi-supervised unmixing
- sparse unmixing
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/2308.04771.pdf
url_code: https://github.com/BehnoodRasti/SUnAA
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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
slides: ""
---
