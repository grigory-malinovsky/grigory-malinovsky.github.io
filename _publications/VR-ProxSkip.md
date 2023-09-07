---
title: "Variance Reduced ProxSkip: Algorithm, Theory and Application to Federated Learning"
collection: publications
permalink: /publication/VR-ProxSkip
excerpt: 'Grigory Malinovsky, Kai Yi, Peter Richtárik'
date: 2022-07-09 
venue: 'Thirty-sixth Conference on Neural Information Processing Systems (NeurIPS 2022)'
---
[PDF](https://arxiv.org/pdf/2207.04338.pdf), [Cite](https://grigory-malinovsky.github.io/files/vr-proxskip.txt), [arXiv](https://arxiv.org/abs/2207.04338), [Thirty-sixth Conference on Neural Information Processing Systems (NeurIPS 2022)](https://nips.cc/virtual/2022/poster/53291) 


Abstract:
======
We study distributed optimization methods based on the local training (LT) paradigm: achieving communication efficiency by performing richer local gradient-based training on the clients before parameter averaging. Looking back at the progress of the field, we identify 5 generations of LT methods: 1) heuristic, 2) homogeneous, 3) sublinear, 4) linear, and 5) accelerated. The 5th generation, initiated by the ProxSkip method of Mishchenko, Malinovsky, Stich and Richtárik (2022) and its analysis, is characterized by the first theoretical confirmation that LT is a communication acceleration mechanism. Inspired by this recent progress, we contribute to the 5th generation of LT methods by showing that it is possible to enhance them further using variance reduction. While all previous theoretical results for LT methods ignore the cost of local work altogether, and are framed purely in terms of the number of communication rounds, we show that our methods can be substantially faster in terms of the total training cost than the state-of-the-art method ProxSkip in theory and practice in the regime when local computation is sufficiently expensive. We characterize this threshold theoretically, and confirm our theoretical predictions with empirical results.
