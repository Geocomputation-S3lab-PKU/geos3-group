---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'PATRIC: A high performance parallel urban transport simulation framework based
  on traffic clustering'
subtitle: ''
summary: ''
authors:
- Lin Wan
- Ganmin Yin
- Jiahao Wang
- Golan Ben-Dor
- Aleksey Ogulenko
- Zhou Huang
tags:
- Parallel simulation
- Agent-based transportation simulation
- Road network partition
- Traffic cluster
- MATSim
categories: []
date: '2023-01-01'
lastmod: 2024-06-20T12:47:25+08:00
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
publishDate: '2024-06-20T04:47:25.044385Z'
publication_types:
- '2'
abstract: Parallel traffic simulation requires partitioning the road network into
  several components that can be assigned to different computing nodes (CPNs). Existing
  studies focus more on reducing edge-cuts (message-passing pipes between CPNs) to
  decrease synchronization message amongst CPNs for efficiency improvement. However,
  even reducing edge-cuts drastically, the volume of messages transmitted might still
  be high, which does not significantly improve performance. Based on observation
  that some traffic clusters (TCs) exist during simulation, i.e., areas with high
  internal and low external traffic density. For high-performance urban transport
  simulation, we propose a data-driven parallel approach named PATRIC, which can generate
  parallel partitions automatically based on traffic clustering. Specifically, the
  TC-based automatic partitioner (TAP) is designed to automatically identify TCs and
  then construct partitions in parallel. We present a partition-growing algorithm
  that prevents traffic-intensive TCs being split across multiple CPNs when distributing
  computing workloads, resulting in more balanced load and fewer synchronization operations.
  Unlike prior work using fixed thresholds for load balancing, we develop the adaptive
  partition updater (APU) to fit the dynamic traffic in the road network, which achieves
  a better trade-off between balancing workload and lowering communication for higher
  efficiency. Experiments on real-world datasets demonstrate that our approach outperforms
  the state-of-the-art methods.
publication: '*Simulation Modelling Practice and Theory*'
doi: https://doi.org/10.1016/j.simpat.2023.102775
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S1569190X23000527
---
