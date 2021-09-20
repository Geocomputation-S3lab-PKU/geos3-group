---
title: "HiSpatialCluster: A Novel High-Performance Software Tool for Clustering Massive Spatial Points"
date: 2018-01-01
publishDate: 2021-09-20T08:48:38.372387Z
authors: ["Yiran Chen", "Zhou Huang", "Tao Pei", "Yu Liu"]
publication_types: ["2"]
abstract: "In the era of big data, spatial clustering is a very important means for geo-data analysis. When clustering big geo-data such as social media check-in data, geotagged photos, and taxi trajectory points, traditional spatial clustering algorithms are facing more challenges. On the one hand, existing spatial clustering tools cannot support the clustering of massive point sets; on the other hand, there is no perfect solution for self-adaptive spatial clustering. In order to achieve clustering of millions or even billions of points adaptively, a new spatial clustering tool— HiSpatialCluster— was proposed, in which the CFSFDP (clustering by fast search and finding density peaks) idea to find cluster centers and the DBSCAN (density-based spatial clustering of applications with noise) idea of density-connect filtering for classification are introduced. The tool's source codes and other resources have been released on Github, and experimental evaluation was performed through clustering massive taxi trajectory points and Flickr geotagged photos in Beijing, China. The spatial clustering results were compared with those through K-means and DBSCAN as well. As a spatial clustering tool, HiSpatialCluster is expected to play a fundamental role in big geo-data research. First, this tool enables clustering adaptively on massive point datasets with uneven spatial density distribution. Second, the density-connect filter method is applied to generate homogeneous analysis units from geotagged data. Third, the tool is accelerated by both parallel CPU and GPU computing so that millions or even billions of points can be clustered efficiently."
featured: false
publication: "*Transactions in GIS*"
doi: "10.1111/tgis.12463"
---

