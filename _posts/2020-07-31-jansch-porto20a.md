---
title: 'Policy Learning of MDPs with Mixed Continuous/Discrete Variables: A Case Study
  on  Model-Free Control of Markovian Jump Systems'
abstract: 'Markovian jump linear systems (MJLS) are an important class of dynamical
  systems that arise in many control applications. In this paper, we introduce the
  problem of controlling unknown MJLS as a new reinforcement learning benchmark for
  Markov decision processes with mixed continuous/discrete state variables. Compared
  with the traditional linear quadratic regulator (LQR), our proposed problem leads
  to a special hybrid MDP (with mixed continuous and discrete variables) and poses
  significant new challenges due to the appearance of an underlying Markov jump parameter
  governing the mode of the system dynamics. Specifically, the state of a MJLS does
  not form a Markov chain and hence one cannot study the MJLS control problem as a
  MDP with solely continuous state variable. However, one can augment the state and
  the jump parameter to obtain a MDP with a mixed continuous-discrete state space.
  We discuss how control theory sheds light on the policy parameterization of such
  hybrid MDPs. Using a recently developed policy gradient results for MJLS, we show
  that we can use data-driven methods to solve the discounted cost version of the
  LQR problem. We modify the widely used natural policy gradient method to directly
  learn the optimal state feedback control policy for MJLS without identifying either
  the system dynamics or the transition probability of the switching parameter. We
  implement the (data-driven) natural policy gradient method on different MJLS examples.
  Our simulation results suggest that the natural gradient method can efficiently
  learn the optimal controller for MJLS with unknown dynamics. '
layout: inproceedings
series: Proceedings of Machine Learning Research
id: jansch-porto20a
month: 0
tex_title: 'Policy Learning of MDPs with Mixed Continuous/Discrete Variables: A Case
  Study on  Model-Free Control of Markovian Jump Systems'
firstpage: 947
lastpage: 957
page: 947-957
order: 947
cycles: false
bibtex_author: Jansch-Porto, Joao Paulo and Hu, Bin and Dullerud, Geir
author:
- given: Joao Paulo
  family: Jansch-Porto
- given: Bin
  family: Hu
- given: Geir
  family: Dullerud
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
pdf: http://proceedings.mlr.press/v120/jansch-porto20a/jansch-porto20a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
