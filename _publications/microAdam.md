---
title: "MicroAdam: Accurate Adaptive Optimization with Low Space Overhead and Provable Convergence"
collection: publications
permalink: /publication/MicroAdam
excerpt: 'Ionut-Vlad Modoranu, Mher Safaryan, Grigory Malinovsky, Eldar Kurtic, Thomas Robert, Peter Richtarik, Dan Alistarh'
date: 2024-06-01
venue: 'The Thirty-Eighth Annual Conference on Neural Information Processing Systems (NeurIPS 2024)'
---

[PDF](https://arxiv.org/pdf/2405.15593), [Cite](https://grigory-malinovsky.github.io/files/microadam.txt), [arXiv](https://arxiv.org/abs/2405.15593), [The Thirty-Eighth Annual Conference on Neural Information Processing Systems (NeurIPS 2024)](https://nips.cc/virtual/2024/poster/95023) 

Abstract:
======
We propose a new variant of the Adam optimizer [Kingma and Ba, 2014] called MICROADAM that specifically minimizes memory overheads, while maintaining theoretical convergence guarantees. We achieve this by compressing the gradient information before it is fed into the optimizer state, thereby reducing its memory footprint significantly. We control the resulting compression error via a novel instance of the classical error feedback mechanism from distributed optimization [Seide et al., 2014, Alistarh et al., 2018, Karimireddy et al., 2019] in which the error correction information is itself compressed to allow for practical memory gains. We prove that the resulting approach maintains theoretical convergence guarantees competitive to those of AMSGrad, while providing good practical performance. Specifically, we show that MICROADAM can be implemented efficiently on GPUs: on both million-scale (BERT) and billion-scale (LLaMA) models, MicroAdam provides practical convergence competitive to that of the uncompressed Adam baseline, with lower memory usage and similar running time.
