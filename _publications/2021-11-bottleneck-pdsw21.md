---
title: "I/O Bottleneck Detection and Tuning:Connecting the Dots using Interactive Log Analysis"
collection: publications
permalink: /publication/2021-11-bottleneck-pdsw21
excerpt: 'Jean Luca Bez, Houjun Tang, Bing Xie, David Williams-Young, Rob Latham, Rob Ross, Sarp Oral, Suren Byna'
date: 2021-11-15
venue: 'PDSW'
paperurl: 'https://xiexbing.github.io/files/PDSW_2021___DXT_Explorer.pdf'
---
Using  parallel  file  systems  efficiently  is  a  trickyproblem due to inter-dependencies among multiple layers of I/Osoftware, including high-level I/O libraries (HDF5, netCDF, etc.),MPI-IO, POSIX, and file systems (GPFS, Lustre, etc.). Profilingtools  such  as  Darshan  collect  traces  to  help  understand  the  I/Operformance  behavior.  However,  there  are  significant  gaps  inanalyzing  the  collected  traces  and  then  applying  tuning  optionsoffered by various layers of I/O software. Seeking to connect thedots  between  I/O  bottleneck  detection  and  tuning,  we  proposeDXT  Explorer,  an  interactive  log  analysis  tool.  In  this  paper,we  present  a  case  study  using  our  interactive  log  analysis  toolto  identify  and  apply  various  I/O  optimizations.  We  report  anevaluation  of  performance  improvement  achieved  for  four  I/Okernels  extracted  from  science  applications.

[Full Paper](https://xiexbing.github.io/files/PDSW_2021___DXT_Explorer.pdf)
