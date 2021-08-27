---
title: "WIRE: Resource-efficient Scaling with Online Prediction for DAG-based Workflows"
collection: publications
permalink: /publication/2021-09-wire-cluster21
excerpt: 'Bing Xie, Qiang Cao, Mayuresh Kunjir, Linli Wan, Jeff Chase, Anirban Mandal, Mats Rynge'
date: 2021-09-08
venue: 'Cluster'
paperurl: 'https://xiexbing.github.io/files/wire_cluster.pdf'
---
This  paper  introduces  WIRE  that  manages  resources  for  the  DAG-based  workflows  on  IaaS  clouds.  WIRE predicts and plans resources over the MAPE (Monitor-Analyze-Plan-Execute)  loops  to:  1)  Estimate  task  performance  with online  data,  2)  Conduct  simulations  to  predict  the  upcomingloads based on online estimates and workflow DAGs, 3) Apply a resource-steering   policy  to   size   cloud   instance  pools   forthe  maximal  parallelism  that  is  consistent  with  low  cost.  Weimplement WIRE on Pegasus WMS/HTCondor and evaluate itsperformance on the ExoGENI network cloud. The results showthat WIRE attains low resource cost with the performance thatis  typically  within  a  factor  of  two  of  optimal.

[Full Paper](https://xiexbing.github.io/files/wire_cluster.pdf)
