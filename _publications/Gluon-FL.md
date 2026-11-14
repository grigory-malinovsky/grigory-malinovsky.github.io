---
title: "Communication-Efficient Gluon in Federated Learning"
collection: publications
permalink: /publication/Gluon-FL
excerpt: 'Xun Qian, Alexander Gaponov, Grigory Malinovsky, Peter Richtárik'
date: 2026-04-12
venue: 'arXiv'
materials:
  - label: Paper
    url: "https://arxiv.org/pdf/2604.10689"
  - label: Cite
    url: "https://grigory-malinovsky.github.io/files/Gluon-FL.txt"
---

[arXiv](https://arxiv.org/abs/2604.10689)

Abstract:
======
Recent developments have shown that Muon-type optimizers based on linear minimization oracles (LMOs) over non-Euclidean norm balls have the potential to get superior practical performance than Adam-type methods in the training of large language models. Since large-scale neural networks are trained across massive machines, communication cost becomes the bottleneck. To address this bottleneck, we investigate Gluon, which is an extension of Muon under the more general layer-wise $(L^0, L^1)$-smooth setting, with both unbiased and contraction compressors. In order to reduce the compression error, we employ the variance reduced technique in SARAH in our compressed methods. The convergence rates and improved communication cost are achieved under certain conditions. As a byproduct, a new variance reduced algorithm with faster convergence rate than Gluon is obtained. We also incorporate momentum variance reduction (MVR) to these compressed algorithms and comparable communication cost is derived under weaker conditions when $L_i^1 \neq 0$. Finally, several numerical experiments are conducted to verify the superior performance of our compressed algorithms in terms of communication cost.
