---
title: "MAST: Model-Agnostic Sparsified Training"
collection: publications
permalink: /publication/MAST
excerpt: 'Yury Demidovich, Grigory Malinovsky, Egor Shulgin, Peter Richtárik'
date: 2023-11-27
venue: 'arXiv'
---

[PDF](https://arxiv.org/pdf/2311.16086.pdf), [Cite](https://grigory-malinovsky.github.io/files/MAST.txt), [arXiv](https://arxiv.org/abs/2311.16086), [Workshop on Nonsmooth Optimization and Applications, NOPTA 2024](https://sites.google.com/view/wnopta) 

Abstract:
======
We introduce a novel optimization problem formulation that departs from the conventional way of minimizing machine learning model loss as a black-box function. Unlike traditional formulations, the proposed approach explicitly incorporates an initially pre-trained model and random sketch operators, allowing for sparsification of both the model and gradient during training. We establish insightful properties of the proposed objective function and highlight its connections to the standard formulation. Furthermore, we present several variants of the Stochastic Gradient Descent (SGD) method adapted to the new problem formulation, including SGD with general sampling, a distributed version, and SGD with variance reduction techniques. We achieve tighter convergence rates and relax assumptions, bridging the gap between theoretical principles and practical applications, covering several important techniques such as Dropout and Sparse training. This work presents promising opportunities to enhance the theoretical understanding of model training through a sparsification-aware optimization approach.
