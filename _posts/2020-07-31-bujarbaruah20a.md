---
title: 'Exploiting Model Sparsity in Adaptive MPC: A Compressed Sensing Viewpoint'
abstract: This paper proposes an Adaptive Stochastic Model Predictive Control (MPC)
  strategy for stable linear time-invariant systems in the presence of bounded disturbances.
  We consider multi-input, multi-output systems that can be expressed by a Finite
  Impulse Response (FIR) model. The parameters of the FIR model corresponding to each
  output are unknown but assumed sparse. We estimate these parameters using the Recursive
  Least Squares algorithm. The estimates are then improved using set-based bounds
  obtained by solving the Basis Pursuit Denoising problem. Our approach is able to
  handle hard input constraints and probabilistic output constraints. Using tools
  from distributionally robust optimization, we reformulate the probabilistic output
  constraints as tractable convex second-order cone constraints, which enables us
  to pose our MPC design task as a convex optimization problem. The efficacy of the
  developed algorithm is highlighted with a thorough numerical example, where we demonstrate
  performance gain over the counterpart algorithm of Bujarbaruah et al. (2018), which
  does not utilize the sparsity information of the system impulse response parameters
  during control design.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: bujarbaruah20a
month: 0
tex_title: 'Exploiting Model Sparsity in Adaptive MPC: A Compressed Sensing Viewpoint'
firstpage: 137
lastpage: 146
page: 137-146
order: 137
cycles: false
bibtex_author: Bujarbaruah, Monimoy and Vallon, Charlott
author:
- given: Monimoy
  family: Bujarbaruah
- given: Charlott
  family: Vallon
date: 2020-07-31
address: 
publisher: PMLR
container-title: Proceedings of the 2nd Conference on Learning for Dynamics and Control
volume: '120'
genre: inproceedings
issued:
  date-parts:
  - 2020
  - 7
  - 31
pdf: http://proceedings.mlr.press/v120/bujarbaruah20a/bujarbaruah20a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
