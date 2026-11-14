---
title: "How Does Muon Work in Private Deep Learning? Scalable Differentially Private Training via Orthogonalization"
collection: publications
permalink: /publication/DP-Muon
excerpt: 'Alexander Gaponov, Grigory Malinovsky, Egor Shulgin, Peter Richtárik'
date: 2026-10-17
venue: 'arXiv'
---

[PDF](https://arxiv.org/pdf/2610.24736), [Cite](https://grigory-malinovsky.github.io/files/DP-Muon.txt), [arXiv](https://arxiv.org/abs/2610.24736)

Abstract:
======
Training deep neural networks requires optimizers that balance computational efficiency with formal data privacy. While orthogonalized update rules, such as the recently introduced Muon optimizer, have shown strong empirical performance and scalability, their behavior under Differential Privacy (DP) is not yet understood. In this paper, we propose DP-Muon, a differentially private variant of the Muon optimizer. By analyzing Muon's orthogonalized updates through the lens of a Linear Minimization Oracle (LMO), we show that the leading effect of per-example clipping is a positive rescaling of the gradient, to which the LMO is blind, so that only a small directional residual controlled by the centered gradient variance enters the optimization error. This yields an $\mathcal O(K^{-1/4})$ convergence rate, up to logarithmic factors, to a clipping-dependent neighborhood at a fixed noise scale and, with noise calibrated to a fixed $(\varepsilon,\delta)$ budget, the standard $(\sqrt d/(n\varepsilon))^{1/2}$ privacy--utility bound of DP-SGD, without assuming bounded gradients. Furthermore, we investigate the hyperparameter landscape of DP-Muon and document how the optimal learning rate, momentum, and batch size change under privacy. Empirically, on image classification DP-Muon matches or improves on DP-SGD and DP-Adam, whereas on language modeling the best optimizer depends on the batch size, with DP-Muon best at small batches and DP-Adam best near the privacy-optimal batch size.
