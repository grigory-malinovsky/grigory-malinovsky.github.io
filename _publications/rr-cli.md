---
title: "Federated Learning with Regularized Client Participation"
collection: publications
permalink: /publication/FedLearn-PP
excerpt: 'Grigory Malinovsky, Samuel Horváth, Konstantin Burlachenko, Peter Richtárik'
date: 2023-02-7
venue: 'arXiv'
---

[PDF](https://arxiv.org/pdf/2302.03662.pdf), [Cite](https://grigory-malinovsky.github.io/files/5gcs.txt), [arXiv](https://arxiv.org/abs/2302.03662), [Federated Learning and Analytics in Practice: Algorithms, Systems, Applications, and Opportunities

Workshop at ICML 2023](https://fl-icml2023.github.io) 

Abstract:
======
Federated Learning (FL) is a distributed machine learning approach where multiple clients work together to solve a machine learning task. One of the key challenges in FL is the issue of partial participation, which occurs when a large number of clients are involved in the training process. The traditional method to address this problem is randomly selecting a subset of clients at each communication round. In our research, we propose a new technique and design a novel regularized client participation scheme. Under this scheme, each client joins the learning process every $R$ communication rounds, which we refer to as a meta epoch. We have found that this participation scheme leads to a reduction in the variance caused by client sampling. Combined with the popular FedAvg algorithm (McMahan et al., 2017), it results in superior rates under standard assumptions. For instance, the optimization term in our main convergence bound decreases linearly with the product of the number of communication rounds and the size of the local dataset of each client, and the statistical term scales with step size quadratically instead of linearly (the case for client sampling with replacement), leading to better convergence rate $\mathcal{O}\left(\frac{1}{T^2}\right)$ compared to $\mathcal{O}\left(\frac{1}{T}\right)$, where $T$ is the total number of communication rounds. Furthermore, our results permit arbitrary client availability as long as each client is available for training once per each meta epoch.
