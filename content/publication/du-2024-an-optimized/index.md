---
# Documentation: https://wowchemy.com/docs/managing-content/

title: An Optimized Edge-Focused Siamese Network for Monitoring New Illegal Buildings
  Using Satellite Images
subtitle: ''
summary: ''
authors:
- Haode Du
- Zhou Huang
- Yi Zhang
tags:
- Buildings;Satellite images;Remote sensing;Feature extraction;Deep learning;Databases;Law;Change
  detection;edge focus;illegal building monitoring;Siamese network
categories: []
date: '2024-00-01'
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
publishDate: '2024-06-19T04:02:19.673971Z'
publication_types:
- '2'
abstract: 'Illegal construction is a common problem often encountered by cities with
  rapid development, which is hard to deal with for multiple reasons. Although these
  illegal buildings are primarily defined by laws and regulations, they still have
  physical characteristics in common that makes them identifiable. In this study,
  we propose an illegal building monitoring method based on satellite images and deep
  learning techniques, named illegal building monitoring network (IBMNet), to improve
  the data collection capacity for monitoring new illegal buildings. IBMNet is an
  end-to-end pixelwise segmentation network with two flows: the Segment Flow, which
  includes a Siamese encoder and an attention fusion module (AFM), and the Edge Flow,
  which uses Gated Convolutional Layers to extract edge information. We implement
  and evaluate our model in China, a country with fast development and struggling
  with illegal buildings. In addition to the conventional metrics, we propose a set
  of specialized metrics to evaluate the model’s ability to discriminate illegal buildings
  and legal buildings ( $text OA_B$ ,  $text F1_B$ , and  $text IoU_B$ ). The model
  achieves great results on the illegal building monitoring dataset (IBMD) with an  $F1$  score
  of 0.7990 and  $text IoU_B$  of 0.7449, showing its great ability in detecting illegal
  buildings in various scenarios and distinguishing them from legal buildings. Compared
  to the existing methods based on urban database, IBMNet has a higher time resolution
  and a larger space coverage, making it more accessible in data and cost-effective
  for governments. The proposed method is also promising in other cities and countries
  with similar problems.'
publication: '*IEEE Transactions on Geoscience and Remote Sensing*'
doi: 10.1109/TGRS.2024.3379567
---
