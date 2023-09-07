---
title: "ProxSkip: Yes! Local Gradient Steps Provably Lead to Communication Acceleration! Finally!"
collection: publications
permalink: /publication/proxskip
excerpt: 'Konstantin Mishchenko, Grigory Malinovsky, Sebastian Stich, Peter Richtárik'
date: 2022-06-09
venue: 'Thirty-ninth International Conference on Machine Learning (ICML 2022)'
---

[PDF](https://arxiv.org/pdf/2202.09357.pdf), [Cite](https://grigory-malinovsky.github.io/files/proxskip.txt), [arXiv](https://arxiv.org/abs/2202.09357), [ICML 2022](https://icml.cc/Conferences/2022/AcceptedPapersInitial) 

Abstract:
======
We introduce ProxSkip -- a surprisingly simple and provably efficient method for minimizing the sum of a smooth (f) and an expensive nonsmooth proximable (ψ) function. The canonical approach to solving such problems is via the proximal gradient descent (ProxGD) algorithm, which is based on the evaluation of the gradient of f and the prox operator of ψ in each iteration. In this work we are specifically interested in the regime in which the evaluation of prox is costly relative to the evaluation of the gradient, which is the case in many applications. ProxSkip allows for the expensive prox operator to be skipped in most iterations: while its iteration complexity is $\mathcal{O}\left(\kappa \log \frac{1}{\varepsilon}\right)$,  where  $\kappa$ is the condition number of $f$, the number of prox evaluations is  $\mathcal{O}\left(\sqrt{\kappa} \log \frac{1}{\varepsilon}\right)$ only. Our main motivation comes from federated learning, where evaluation of the gradient operator corresponds to taking a local GD step independently on all devices, and evaluation of prox corresponds to (expensive) communication in the form of gradient averaging. In this context, ProxSkip offers an effective acceleration of communication complexity. Unlike other local gradient-type methods, such as FedAvg, SCAFFOLD, S-Local-GD and FedLin, whose theoretical communication complexity is worse than, or at best matching, that of vanilla GD in the heterogeneous data regime, we obtain a provable and large improvement without any heterogeneity-bounding assumptions.
