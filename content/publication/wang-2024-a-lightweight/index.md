---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A lightweight multi-layer perceptron for efficient multivariate time series
  forecasting
subtitle: ''
summary: ''
authors:
- Zhenghong Wang
- Sijie Ruan
- Tianqiang Huang
- Haoyi Zhou
- Shanghang Zhang
- Yi Wang
- Leye Wang
- Zhou Huang
- Yu Liu
tags:
- Time-series forecasting
- Multilayer perceptron
- Long-range forecasting
- Traffic Forecasting
- Spatial–Temporal Graph Neural Network
categories: []
date: '2024-01-01'
lastmod: 2024-06-19T12:08:34+08:00
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
publishDate: '2024-06-19T04:08:34.442525Z'
publication_types:
- '2'
abstract: Efficient and effective multivariate time series (MTS) forecasting is critical
  for real-world applications, such as traffic management and energy dispatching.
  Most of the current deep learning studies (e.g., Spatio-Temporal Graph Neural Networks
  and Transformers) fall short in a trade-off between performance and efficiency.
  Existing MTS forecasting studies have yet to fully and simultaneously address issues
  such as modelling both temporal and variate dependencies, as well as the temporal
  locality, hindering broader applications. In this paper, we propose a lightweight
  model, i.e., Time Series MLP (TSP). TSP is built upon MLP and relies on the PrecMLP
  with the proposed computationally free Precurrent mechanism to model both the variate
  dependency and temporal locality, thus being simple, effective and versatile. Extensive
  experiments show that TSP outperforms state-of-the-art methods on 16 datasets for
  both Long-term Time-series Forecasting and Traffic Forecasting tasks. Furthermore,
  it attains a significant reduction of at least 95.97% in practical training speed
  on the CPU.
publication: '*Knowledge-Based Systems*'
doi: https://doi.org/10.1016/j.knosys.2024.111463
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0950705124000984
---
