---
title: "Accelerating Collective Communication in Data Parallel Trainingacross Deep Learning Frameworks"
collection: publications
permalink: /publication/2022-04-acodl-nsdi22
excerpt: 'Joshua Romero, Junqi Yin, Nouamane Laanait, Bing Xie, M. Todd Young, Sean Treichler, Vitalii Starchenko, Albina Borisevich, Alex Sergeev, Michael Matheson'
date: 2022-04-06
venue: 'NSDI'
paperurl: 'https://xiexbing.github.io/files/acodl_nsdi.pdf'
---
This work develops new techniques within Horovod, a generic communication library supporting data parallel training across deep  learning  frameworks. In  particular, we  improve  the Horovod  control  plane  by  implementing  a  new  coordination scheme that takes advantage of the characteristics of the typical data parallel training paradigm, namely the repeated execution of collectives on the gradients of a fixed set of tensors. Using a caching strategy, we execute Horovod’s existing coordinator-worker logic only once during a typical training run, replacing it with a more efficient decentralizedorchestration  strategy using  the  cached data  and a  global intersection of a bitvector for the remaining training duration. Next, we introduce a feature for end users to explicitly group collective operations, enabling finer grained control over the communication buffer sizes. To evaluate our proposed strategies, we conduct experiments on a world-classsupercomputer — Summit.  We compare our proposals to Horovod’s original design and observe 2× performance improvement at a scale of 6000 GPUs; we also compare them against tf.distribute and torch.DDP and achieve 12% better and comparable performance, respectively, using up to 1536 GPUs; we compare our solution against BytePS in typical HPC settings and achieve about 20% better performance on a scale of 768 GPUs. Finally, we test our strategies on a scientific application (STEMDL) using up to 27,600 GPUs (the entire Summit) and show that we achieve a near-linear scaling of 0.93 with a sustained performance of 1.54 exaflops (with standard error +- 0.02) in FP16 precision.

[Full Paper](https://xiexbing.github.io/files/acodl_nsdi.pdf)