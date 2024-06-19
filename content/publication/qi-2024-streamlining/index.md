---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Streamlining trajectory map-matching: a framework leveraging spark and GPU-based
  stream processing'
subtitle: ''
summary: ''
authors:
- Houji Qi
- Zhou Huang
- Yiran Chen
- Yi Zhang
- Yong Gao
tags: []
categories: []
date: '2024-01-01'
lastmod: 2024-06-19T12:02:19+08:00
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
publishDate: '2024-06-19T04:02:19.442588Z'
publication_types:
- '2'
abstract: ' Real-time online trajectory map-matching has emerged as a critical component
  in the era of location-based services (LBS) and intelligent transportation systems
  (ITS). It refers to the process of aligning a user’s GPS trajectory data with the
  corresponding road network in real-time. This technology has significant implications
  for various industries and applications. As our reliance on LBS and ITS continues
  to grow, the demand for faster, more accurate, and more reliable trajectory map-matching
  methods becomes increasingly important. Contemporary online map-matching predominantly
  employs stream processing techniques. Based on stream processing frameworks, we
  propose a heterogeneous hybrid architecture for map-matching. The architecture integrates
  Spark Streaming and graphics processing unit (GPU) heterogeneous computing for the
  first time. The hidden Markov model is employed as the map-matching algorithm, and
  Spark Streaming serves as the distributed processing platform. We conduct map-matching
  experiments using a GPS taxi trajectory dataset in Beijing’s Haidian District. The
  results demonstrate that in comparison to other analogous research, our framework’s
  performance has increased by over ten times, possessing a superior data processing
  capability and lower latency. This research provides a novel approach of stream-based
  heterogeneous computation for processing large-scale geographic data. '
publication: '*International Journal of Geographical Information Science*'
doi: 10.1080/13658816.2024.2337225
links:
- name: URL
  url: https://doi.org/10.1080/13658816.2024.2337225
---
