---
title: "Parameter-Agnostic Error Feedback Enhanced With Hessian-Corrected Momentum"
collection: publications
permalink: /publication/EF-Hessian-Momentum
excerpt: 'Abdurakhmon Sadiev, Yury Demidovich, Grigory Malinovsky, Igor Sokolov, Sarit Khirirat, Peter Richtárik'
date: 2025-11-18
venue: 'The 17th Annual Workshop on Optimization for Machine Learning (OPT 2025, NeurIPS Workshop)'
---

[PDF](https://opt-ml.org/papers/2025/paper52.pdf), [Cite](https://grigory-malinovsky.github.io/files/EF-Hessian-Momentum.txt), [arXiv](https://arxiv.org/abs/2511.14501), [OPT 2025 (NeurIPS Workshop)](https://opt-ml.org/papers/2025/paper52.pdf)

Abstract:
======
Advanced machine learning models often rely on massive datasets distributed across many nodes. To reduce communication overhead in large-scale stochastic optimization, compression is widely used, though it may introduce noise and harm convergence. Error feedback mitigates this by accumulating and reusing compression error, while Hessian-vector products provide variance reduction and improve complexity. Building on these ideas, we design a distributed algorithm for finding $\varepsilon$-stationary points of nonconvex $L$-smooth functions that leverages error feedback, normalization, and second-order momentum. Unlike prior methods requiring problem parameters to tune stepsizes, our algorithm is parameter-agnostic: it uses $\mathcal{O}(1)$ batch size and a time-varying learning rate independent of $L$ and the functional gap. The method achieves $\mathcal{O}(\varepsilon^{-3})$ communication complexity.
