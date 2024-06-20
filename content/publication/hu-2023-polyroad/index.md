---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'PolyRoad: Polyline Transformer for Topological Road-Boundary Detection'
subtitle: ''
summary: ''
authors:
- Yuan Hu
- Zhibin Wang
- Zhou Huang
- Yu Liu
tags:
- Roads
- Feature extraction
- Transformers
- Iterative methods
- Computer architecture
- Training
- Task analysis
- Polyline detection
- polyline losses
- polyline matching
- road-boundary detection
- transformers
categories: []
date: '2024-00-01'
lastmod: 2024-06-20T12:23:07+08:00
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
publishDate: '2024-06-20T04:23:06.581247Z'
publication_types:
- '2'
abstract: 'Topological road-boundary detection using remote sensing imagery plays
  a critical role in creating high-definition (HD) maps and enabling autonomous driving.
  Previous approaches follow an iterative graph-growing paradigm for road-boundary
  extraction, where road boundaries are predicted vertex by vertex and instance by
  instance to output a graph, resulting in limitations of low inference speed. In
  this work, we formulate the road boundaries as polylines instead of a graph and
  propose a novel polyline transformer for topological road-boundary detection, termed
  PolyRoad. PolyRoad is built on the transformer architecture and is capable of detecting
  all road boundaries in parallel, which greatly improves the training and inference
  speed compared with the graph-based methods. To perform bipartite matching between
  the ground truth and predicted polylines, we develop a polyline matching cost to
  measure the distance, considering the order of open and closed polylines. In addition,
  we propose three different losses for supervising polyline learning: the order-oriented  $L1$  loss,
  direction loss, and mask loss. The order-oriented  $L1$  loss provides the point-level
  supervision to constrain the absolute position of each point of the road-boundary
  polylines. The direction loss provides the direction-level supervision to constrain
  the geometry shape of the predicted polylines by supervising the relative position
  of adjacent points. The mask loss provides the pixel-level supervision of the predicted
  polylines by converting the vector-format polylines into raster-format binary masks.
  Comprehensive experiments are conducted on the Topo-boundary dataset. Quantitative
  and qualitative results show that PolyRoad achieves superior performance than prior
  methods in both pixel-level and geometry-level metrics. More notably, PolyRoad achieves  $3.37
  times $  and  $22.85 times $  faster inference speeds than Enhanced-iCurb and VecRoad,
  respectively.'
publication: '*IEEE Transactions on Geoscience and Remote Sensing*'
doi: 10.1109/TGRS.2023.3344103
---
