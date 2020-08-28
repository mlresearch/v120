---
title: Model-Predictive Planning via Cross-Entropy and Gradient-Based Optimization
abstract: Recent works in high-dimensional model-predictive control and model-based
  reinforcement learning with learned dynamics and reward models have resorted to
  population-based optimization methods, such as the Cross-Entropy Method (CEM), for
  planning a sequence of actions. To decide on an action to take, CEM conducts a search
  for the action sequence with the highest return according to the learned dynamics
  model and reward. Action sequences are typically randomly sampled from an unconditional
  Gaussian distribution and evaluated. This distribution is iteratively updated towards
  action sequences with higher returns. However, sampling and simulating unconditional
  action sequences can be very inefficient (especially from a diagonal Gaussian distribution
  and for high dimensional action spaces). An alternative line of approaches optimize
  action sequences directly via gradient descent but are prone to local optima. We
  propose a method to solve this planning problem by interleaving CEM and gradient
  descent steps in optimizing the action sequence.
layout: inproceedings
series: Proceedings of Machine Learning Research
issn: 2640-3498
id: bharadhwaj20a
month: 0
tex_title: Model-Predictive Control via Cross-Entropy and Gradient-Based Optimization
firstpage: 277
lastpage: 286
page: 277-286
order: 277
cycles: false
bibtex_author: Bharadhwaj, Homanga and Xie, Kevin and Shkurti, Florian
author:
- given: Homanga
  family: Bharadhwaj
- given: Kevin
  family: Xie
- given: Florian
  family: Shkurti
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
pdf: http://proceedings.mlr.press/v120/bharadhwaj20a/bharadhwaj20a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
