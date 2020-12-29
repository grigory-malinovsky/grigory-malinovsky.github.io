---
title: "From Local SGD to Local Fixed-Point Methods for Federated Learning"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'Grigory Malinovsky, Dmitry Kovalev, Elnur Gasanov, Laurent Condat, Peter Richtárik'
date: 2020-07-13
venue: 'The Thirty-seventh International Conference on Machine Learning (ICML 2020)'
---
[PDF](https://arxiv.org/pdf/2004.01442.pdf), [Cite](https://scholar.googleusercontent.com/scholar.bib?q=info:PWDNmqH2cJ8J:scholar.google.com/&output=citation&scisdr=CgXs1Zy1EKfp3RDjRo4:AAGBfm0AAAAAX-rmXo4TbJTa8Sfkh6FuJv5Of0JLZ5fe&scisig=AAGBfm0AAAAAX-rmXkYEn1cNtDIdNQ4_hSoBmtqJJofo&scisf=4&ct=citation&cd=-1&hl=ru&scfhb=1), [Google Scholar](https://scholar.google.com/citations?hl=ru&user=4w2W9KQAAAAJ#d=gs_md_cita-d&u=%2Fcitations%3Fview_op%3Dview_citation%26hl%3Dru%26user%3D4w2W9KQAAAAJ%26citation_for_view%3D4w2W9KQAAAAJ%3Au5HHmVD_uO8C%26tzom%3D-180), [arXiv](https://arxiv.org/abs/2004.01442), [PMLR 119](http://proceedings.mlr.press/v119/malinovskiy20a.html), [ICML 2020](https://icml.cc/virtual/2020/poster/6590)
Abstract:
======
Most algorithms for solving optimization problems or finding saddle points of convex-concave functions are fixed-point algorithms. In this work we consider the generic problem of finding a fixed point of an average of operators, or an approximation thereof, in a distributed setting. Our work is motivated by the needs of federated learning. In this context, each local operator models the computations done locally on a mobile device. We investigate two strategies to achieve such a consensus: one based on a fixed number of local steps, and the other based on randomized computations. In both cases, the goal is to limit communication of the locally-computed variables, which is often the bottleneck in distributed frameworks. We perform convergence analysis of both methods and conduct a number of experiments highlighting the benefits of our approach.


