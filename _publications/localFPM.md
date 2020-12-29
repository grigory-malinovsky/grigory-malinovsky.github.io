---
title: "From Local SGD to Local Fixed-Point Methods for Federated Learning"
collection: publications
permalink: /publication/localFPM
excerpt: 'Grigory Malinovsky, Dmitry Kovalev, Elnur Gasanov, Laurent Condat, Peter Richtárik'
date: 2020-07-13
venue: 'The Thirty-seventh International Conference on Machine Learning (ICML 2020)'
---
[PDF](https://arxiv.org/pdf/2004.01442.pdf), [Cite](https://grigory-malinovsky.github.io/files/local.txt), [arXiv](https://arxiv.org/abs/2004.01442), [PMLR 119](http://proceedings.mlr.press/v119/malinovskiy20a.html), [ICML 2020](https://icml.cc/virtual/2020/poster/6590)
Abstract:
======
Most algorithms for solving optimization problems or finding saddle points of convex-concave functions are fixed-point algorithms. In this work we consider the generic problem of finding a fixed point of an average of operators, or an approximation thereof, in a distributed setting. Our work is motivated by the needs of federated learning. In this context, each local operator models the computations done locally on a mobile device. We investigate two strategies to achieve such a consensus: one based on a fixed number of local steps, and the other based on randomized computations. In both cases, the goal is to limit communication of the locally-computed variables, which is often the bottleneck in distributed frameworks. We perform convergence analysis of both methods and conduct a number of experiments highlighting the benefits of our approach.


