---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Spatiotemporal Fusion Transformer for large-scale traffic forecasting
subtitle: ''
summary: ''
authors:
- Zhenghong Wang
- Yi Wang
- Furong Jia
- Fan Zhang
- Nikita Klimenko
- Leye Wang
- Zhengbing He
- Zhou Huang
- Yu Liu
tags:
- Traffic flow forecasting
- Transformer
- Graph Neural Network
- Large-scale traffic
- Collaborative forecasting
categories: []
date: '2024-01-01'
lastmod: 2024-06-19T12:08:35+08:00
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
publishDate: '2024-06-19T04:08:34.978228Z'
publication_types:
- '2'
abstract: 'The way humans travel and even their daily commute, is gradually expanding
  beyond the confines of counties and cities. Traffic between counties, cities, and
  even across the entire state is increasingly becoming a common aspect of daily activities.
  The demand for traffic flow forecasting covering larger geographical areas and longer
  time spans is ongoing. However, existing studies lack targeted deep model proposals
  for large-scale forecasting. To address this gap, we propose Spatiotemporal Fusion
  Transformer (STFT). Specifically, we propose three modules on top of the Transformer
  architecture: (i) Seasonality Encoding, based on the multi-periodicity inherent
  in traffic flow to facilitate the extraction of more predictable time-variant components
  from complex patterns. (ii) Tubelet Embedding, partitioning the input into Tubelets
  as input tokens for the Transformer. The Tubelet design not only achieves quadratic
  reductions in computational and memory usage but also enhances spatiotemporal locality
  feature modelling. (iii) Token Permutator, leveraging diffusion graph to model the
  spatiotemporal dynamics as a token permutation process. The graph representation
  is then projected by a proposed Hadamard Mapper to circumvent the anomaly sensitivities
  of Graph Neural Networks in large-scale computations. Experimental results on five
  real-world datasets indicate that STFT can cater to collaborative forecasting at
  diverse scales (subdivision, county, municipal, state) that not only outperforms
  state-of-the-art methods but also enjoys a large speedup of up to 4.46×. Lastly,
  we also find that compared to independent forecasting for each subregion, large-scale
  collaborative forecasting with STFT offers both better feature utilization and requires
  less computational cost.'
publication: '*Information Fusion*'
doi: https://doi.org/10.1016/j.inffus.2024.102293
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S156625352400071X
---
