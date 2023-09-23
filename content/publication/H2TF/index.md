---
title: "H2TF for Hyperspectral Image Denoising: Where Hierarchical Nonlinear Transform Meets Hierarchical Matrix Factorization"
authors:
- Jia-Yi Li
- admin
- Yi-Si Luo
- Xi-Le Zhao
- Jian-Li Wang
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Corresponding author"
- "Corresponding author"
date: "2023-07-13T00:00:00Z"
doi: "10.1109/LGRS.2023.3294933"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-07-13T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Geoscience and Remote Sensing Letters*"
publication_short: ""

abstract: Recently, tensor singular value decomposition (t-SVD) has emerged as a promising tool for hyperspectral image (HSI) processing. In the t-SVD, there are two key building blocks： 1\) the low-rank enhanced transform and 2\) the accompanying low-rank characterization of transformed frontal slices. Previous t-SVD methods mainly focus on the developments of 1\), while neglecting the other important aspect, i.e., the exact characterization of transformed frontal slices. In this letter, we exploit the potentiality in both building blocks by leveraging the hierarchical nonlinear transform (HSI) and the hierarchical matrix factorization (HMF) to establish a new tensor factorization (termed as H2TF). Compared with shallow counter partners, e.g., low-rank matrix factorization (MF) or its convex surrogates, H2TF can better capture complex structures of transformed frontal slices due to its hierarchical modeling abilities. We then suggest the H2TF-based HSI denoising model and develop an alternating direction method of multipliers-based algorithm to address the resultant model. Extensive experiments validate the superiority of our method over state-of-the-art (SOTA) HSI denoising methods.


tags:
- hyperspectral denoising
- tensor singular value decomposition (t-SVD)
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: ""
url_code: 'https://github.com/jinyu-xie/H2TF'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'A general illustration of the H2TF representation of a tensor X.'
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
slides: []
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}
