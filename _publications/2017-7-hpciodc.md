---
title: "Output performance study on a production petascale filesystem"
collection: publications
permalink: /publication/2017-7-hpciodc
excerpt: 'Bing Xie, Jeff Chase, David Dillow, Scott Klasky, Jay Lofstead, Sarp Oral, Norbert Podhorszki'
date: 2017-07-01
venue: 'HPC IODC Workshop'
paperurl: 'https://xiexbing.github.io/files/hpciodc17.pdf'
---
This paper reports our observations from a top-tier supercomputer Titan and its Lustre parallel file stores under production load.
In summary, we find that supercomputer file systems are highly variable
across the machine at fine time scales. This variability has two major implications. First, stragglers lessen the benefit of coupled I/O parallelism
(striping). Peak median output bandwidths are obtained with parallel
writes to many independent files, with no striping or write-sharing of
files across clients (compute nodes). I/O parallelism is most effective
when the application—or its I/O middleware system—distributes the
I/O load so that each client writes separate files on multiple targets, and
each target stores files for multiple clients, in a balanced way. Second, our
results suggest that the potential benefit of dynamic adaptation is limited. In particular, it is not fruitful to attempt to identify “good spots”
in the machine or in the file system: component performance is driven by
transient load conditions, and past performance is not a useful predictor
of future performance. For example, we do not observe regular diurnal
load patterns.


[Full Paper](https://xiexbing.github.io/files/hpciodc17.pdf)
