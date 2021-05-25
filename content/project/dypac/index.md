---
title: Dypac 
summary: Dynamic Parcel Aggregation with Clustering
tags:
- Machine Learning
- Neuroimaging
- Functional parcellation
date: "2021-05-24T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Dypac uses a simple two level clustering, one on sliding time windows, and one on indicator functions of parcels aggregated over many windows. For the sliding windows, k means runs directly on the time series generating a family of parcels, which are represented with one-hot encoders. The second-level aggregation clustering procedure gives the stable maps. 
  focal_point: Smart

links:
- icon: python
  icon_pack: fab
  name: Pypi
  url: https://pypi.org/project/dypac/
- icon: github
  icon_pack: fab
  name: Code Repository
  url: https://github.com/courtois-neuromod/dypac
url_code: ""
url_pdf: ""
url_slides: ""
url_video: "https://www.youtube.com/watch?v=kq6Vu5c_8qY"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---
