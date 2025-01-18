---
title: "Methods with Local Steps and Random Reshuffling for Generally Smooth Non-Convex Federated Optimization"
collection: publications
permalink: /publication/L0L1FedRR
excerpt: 'Yury Demidovich, Petr Ostroukhov, Grigory Malinovsky, Samuel Horváth, Martin Takáč, Peter Richtárik, Eduard Gorbunov'
date: 2024-10-10
venue: 'arXiv'
---

[PDF](https://arxiv.org/pdf/2412.02781), [Cite](https://grigory-malinovsky.github.io/files/L0L1FedRR.txt), [arXiv](https://arxiv.org/abs/2412.02781)
Abstract:
======
Non-convex Machine Learning problems typically do not adhere to the standard smoothness assumption. Based on empirical findings, Zhang et al. (2020b) proposed a more realistic generalized (L0,L1)-smoothness assumption, though it remains largely unexplored. Many existing algorithms designed for standard smooth problems need to be revised. However, in the context of Federated Learning, only a few works address this problem but rely on additional limiting assumptions. In this paper, we address this gap in the literature: we propose and analyze new methods with local steps, partial participation of clients, and Random Reshuffling without extra restrictive assumptions beyond generalized smoothness. The proposed methods are based on the proper interplay between clients' and server's stepsizes and gradient clipping. Furthermore, we perform the first analysis of these methods under the Polyak-Łojasiewicz condition. Our theory is consistent with the known results for standard smooth problems, and our experimental results support the theoretical insights.
