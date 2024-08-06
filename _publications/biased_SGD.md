---
title: "A Guide Through the Zoo of Biased SGD"
collection: publications
permalink: /publication/biased_SGD
excerpt: 'Yury Demidovich, Grigory Malinovsky, Igor Sokolov, Peter Richtárik'
date: 2023-05-24
venue: 'Thirty-eighth Annual Conference on Neural Information Processing Systems (NeurIPS 2023)'
---

[PDF](https://arxiv.org/pdf/2305.16296.pdf), [Cite](https://grigory-malinovsky.github.io/files/biasedSGD.txt), [arXiv](https://arxiv.org/abs/2305.16296), [NeurIPS 2023](https://proceedings.neurips.cc/paper_files/paper/2023/hash/484d254ff80e99d543159440a06db0de-Abstract-Conference.html)

Abstract:
======
Stochastic Gradient Descent (SGD) is arguably the most important single algorithm in modern machine learning. Although SGD with unbiased gradient estimators has been studied extensively over at least half a century, SGD variants relying on biased estimators are rare. Nevertheless, there has been an increased interest in this topic in recent years. However, existing literature on SGD with biased estimators (BiasedSGD) lacks coherence since each new paper relies on a different set of assumptions, without any clear understanding of how they are connected, which may lead to confusion. We address this gap by establishing connections among the existing assumptions, and presenting a comprehensive map of the underlying relationships. Additionally, we introduce a new set of assumptions that is provably weaker than all previous assumptions, and use it to present a thorough analysis of BiasedSGD in both convex and non-convex settings, offering advantages over previous results. We also provide examples where biased estimators outperform their unbiased counterparts or where unbiased versions are simply not available. Finally, we demonstrate the effectiveness of our framework through experimental results that validate our theoretical findings.
