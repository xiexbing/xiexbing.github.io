---
title: "SCTuner: An Autotuner Addressing Dynamic I/O Needs on Supercomputer I/O Subsystems"
collection: publications
permalink: /publication/2021-11-sctuner-pdsw21
excerpt: 'Houjun Tang\*, Bing Xie\*, Suren Byna, Philip Carns, Quincey Koziol, Sudarsun Kannan, Jay Lofstead, Sarp Oral (\* equal contribution)'
date: 2021-11-15
venue: 'PDSW'
paperurl: 'https://xiexbing.github.io/files/hdf5_pdsw_2021.pdf'
---
In  high-performance  computing  (HPC),  scientificapplications   often   manage   a   massive   amount   of   data   usingI/O  libraries.  These  libraries  provide  convenient  data  modelabstractions,  help  ensure  data  portability,  and,  most  important,empower   end   users   to   improve   I/O   performance   by   tuningconfigurations  across  multiple  layers  of  the  HPC  I/O  stack.  Wepropose SCTuner, an autotuner integrated within the I/O libraryitself to dynamically tune both the I/O library and the underlyingI/O  stack  at  application  runtime.  To  this  end,  we  introduce  astatistical benchmarking method to profile the behaviors of indi-vidual supercomputer I/O subsystems with varied configurationsacross I/O layers. We use the benchmarking results as the built-inknowledge in SCTuner, implement an I/O pattern extractor, andplan to implement an online performance tuner as the SCTunerruntime. We conducted a benchmarking analysis on the Summitsupercomputer and its GPFS file system Alpine. The preliminaryresults show that our method can effectively extract the consistentI/O   behaviors   of   the   target   system   under   production   load,building  the  base  for  I/O  autotuning  at  application  runtime.

[Full Paper](https://xiexbing.github.io/files/hdf5-pdsw-2021.pdf)
