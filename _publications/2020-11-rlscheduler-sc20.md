---
title: "RLScheduler: an automated HPC batch job scheduler using reinforcement learning"
collection: publications
permalink: /publication/2020-11-rlscheduler-sc20
excerpt: 'Di Zhang, Dong Dai, Youbiao He, Forrest Sheng Bao, Bing Xie'
date: 2020-11-01
venue: 'SC'
paperurl: 'https://xiexbing.github.io/files/rlscheduler-sc20.pdf'
---
Today’s high-performance computing (HPC) platforms are still dominated by batch jobs. Accordingly, effective
batch job scheduling is crucial to obtain high system efficiency.
Existing HPC batch job schedulers typically leverage heuristic
priority functions to prioritize and schedule jobs. But, once
configured and deployed by the experts, such priority functions
can hardly adapt to the changes of job loads, optimization
goals, or system settings, potentially leading to degraded system
efficiency when changes occur. To address this fundamental issue,
we present RLScheduler, an automated HPC batch job scheduler
built on reinforcement learning. RLScheduler relies on minimal
manual interventions or expert knowledge, but can learn highquality scheduling policies via its own continuous ‘trial and error’. We introduce a new kernel-based neural network structure
and trajectory filtering mechanism in RLScheduler to improve
and stabilize the learning process. Through extensive evaluations,
we confirm that RLScheduler can learn high-quality scheduling
policies towards various workloads and various optimization
goals with relatively low computation cost. Moreover, we show
that the learned models perform stably even when applied to
unseen workloads, making them practical for production use.

[Full Paper](https://xiexbing.github.io/files/rlscheduler-sc20.pdf)
