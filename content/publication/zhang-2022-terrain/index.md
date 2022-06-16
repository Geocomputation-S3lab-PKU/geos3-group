---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Terrain feature-aware deep learning network for digital elevation model superresolution
subtitle: ''
summary: ''
authors:
- Yifan Zhang
- Wenhao Yu
- Di Zhu
tags:
- DEM superresolution
- Terrain features
- Explicit terrain optimization
- Deformable convolution
categories: []
date: '2022-01-01'
lastmod: 2022-06-16T17:05:15+08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-06-16T09:05:14.302789Z'
publication_types:
- '2'
abstract: Neural networks (NNs) have demonstrated the potential to recover finer textural
  details from lower-resolution images by superresolution (SR). Given similar grid-based
  data structures, some researchers have transferred image SR methods to digital elevation
  models (DEMs). These efforts have yielded better results than traditional spatial
  interpolation methods. However, terrain data present inherently different characteristics
  and practical meanings compared with natural images. This makes it unsuitable for
  existing SR methods on perceptually visual features of images to be directly adopted
  for extracting terrain features. In this paper, we argue that the problem lies in
  the lack of explicit terrain feature modeling and thus propose a terrain feature-aware
  superresolution model (TfaSR) to guide DEM SR towards the extraction and optimization
  of terrain features. Specifically, a deep residual module and a deformable convolution
  module are integrated to extract deep and adaptive terrain features, respectively.
  In addition, explicit terrain feature-aware optimization is proposed to focus on
  local terrain feature refinement during training. Extensive experiments show that
  TfaSR achieves state-of-the-art performance in terrain feature preservation during
  DEM SR. Specifically, compared with the traditional bicubic interpolation method
  and existing neural network methods (SRGAN, SRResNet, and SRCNN), the RMSE of our
  results is improved by 1.1% to 23.8% when recovering the DEM from 120 m to 30 m,
  by 4.9% to 22.7% when recovering the DEM from 60 m to 30 m, and by 7.8% to 53.7%
  when recovering the DEM from 30 m to 10 m. The source code that has been developed
  is shared on Figshare (https://doi.org/10.6084/m9.figshare.19597201).
publication: '*ISPRS Journal of Photogrammetry and Remote Sensing*'
doi: https://doi.org/10.1016/j.isprsjprs.2022.04.028
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0924271622001332
---
