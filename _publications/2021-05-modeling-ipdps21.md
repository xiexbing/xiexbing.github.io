---
title: "Interpreting Write Performance of Supercomputer I/O Systems with Regression Models"
collection: publications
permalink: /publication/2021-05-modeling-ipdps21
excerpt: 'Bing Xie, Zilong Tan, Phil Carns, Jeff Chase, Kevin Harms, Jay Lofstead, Sarp Oral, Sudharshan Vazhkudai, Feiyi Wang'
date: 2021-05-10
venue: 'IPDPS'
paperurl: 'https://xiexbing.github.io/files/modeling_ipdps.pdf'
---
This  work  seeks  to  advance  the  state  of  the  art  in HPC I/O performance analysis and interpretation. In particular,we  demonstrate  effective  techniques  to:  (1)  model  output  per-formance  in  the  presence  of  I/O  interference  from  productionloads; (2) build features from write patterns and key parametersof the system architecture and configurations; (3) employ suitablemachine  learning  algorithms  to  improve  model  accuracy.  We train models with five popular regression algorithms and conduct experiments   on   two   distinct   production   HPC   platforms.   We find  that  the  lasso  and  random  forest  models  predict  outputperformance  with  high  accuracy  on  both  of  the  target  systems.We  also  explore  use  of  the  models  to  guide  adaptation  in  I/Omiddleware systems, and show potential for improvements of atleast  15%  from  model-guided  adaptation  on  70%  of  samples,and  improvements  up  to  10x on  some  samples  for  both  of  the target systems.

[Full Paper](https://xiexbing.github.io/files/modeling_ipdps.pdf)
