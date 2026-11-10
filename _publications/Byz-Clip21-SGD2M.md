---
title: "Byzantine-Robust and Differentially Private Federated Optimization under Weaker Assumptions"
collection: publications
permalink: /publication/Byz-Clip21-SGD2M
excerpt: 'Rustem Islamov, Grigory Malinovsky, Alexander Gaponov, Aurelien Lucchi, Peter Richtárik, Eduard Gorbunov'
date: 2026-03-24
venue: 'The 42nd Conference on Uncertainty in Artificial Intelligence (UAI 2026)'
---

[PDF](https://arxiv.org/pdf/2603.23472), [Cite](https://grigory-malinovsky.github.io/files/Byz-Clip21-SGD2M.txt), [arXiv](https://arxiv.org/abs/2603.23472), [UAI 2026](https://www.auai.org/uai2026/)

Abstract:
======
Federated Learning (FL) enables heterogeneous clients to collaboratively train a shared model without centralizing their raw data, offering an inherent level of privacy. However, gradients and model updates can still leak sensitive information, while malicious servers may mount adversarial attacks such as Byzantine manipulation. These vulnerabilities highlight the need to address differential privacy (DP) and Byzantine robustness within a unified framework. Existing approaches, however, often rely on unrealistic assumptions such as bounded gradients, require auxiliary server-side datasets, or fail to provide convergence guarantees. We address these limitations by proposing Byz-Clip21-SGD2M, a new algorithm that integrates robust aggregation with double momentum and carefully designed clipping. We prove high-probability convergence guarantees under standard $L$-smoothness and $\sigma$-sub-Gaussian gradient noise assumptions, thereby relaxing conditions that dominate prior work. Our analysis recovers state-of-the-art convergence rates in the absence of adversaries and improves utility guarantees under Byzantine and DP settings. Empirical evaluations on CNN and MLP models trained on MNIST further validate the effectiveness of our approach.
