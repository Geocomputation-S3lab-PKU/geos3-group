---
title: "High-Performance Spatiotemporal Trajectory Matching across Heterogeneous Data Sources"
date: 2020-04-01
publishDate: 2021-09-20T08:48:38.375427Z
authors: ["Xuri Gong", "Zhou Huang", "Yaoli Wang", "Lun Wu", "Yu Liu"]
publication_types: ["2"]
abstract: "In the era of big data, the movement of the same object or person can be recorded by different devices with different measurement accuracies and sampling rates. Matching and conflating these heterogeneous trajectories help to enhance trajectory semantics, describe user portraits, and discover specified groups from human mobility. In this paper, we proposed a high-performance approach for matching spatiotemporal trajectories across heterogeneous massive datasets. Two indicators, i.e., Time Weighted Similarity (TWS) and Space Weighted Similarity (SWS), are proposed to measure the similarity of spatiotemporal trajectories. The core idea is that trajectories are more similar if they stay close in a longer time and distance. A distributed computing framework based on Spark is built for efficient trajectory matching among massive datasets. In the framework, the trajectory segments are partitioned into 3-dimensional space– time cells for parallel processing, and a novel method of segment reference point is designed to avoid duplicated computation. We conducted extensive matching experiments on real-world and synthetic trajectory datasets. The experimental results illustrate that the proposed approach outperforms other similarity metrics in accuracy, and the Spark-based framework greatly improves the efficiency in spatiotemporal trajectory matching."
featured: false
publication: "*Future Generation Computer Systems*"
tags: ["Distributed computing", "Spatiotemporal big data", "Trajectory matching", "Trajectory similarity"]
doi: "10.1016/j.future.2019.11.027"
---

