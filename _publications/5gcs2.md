---
title: "Improving Accelerated Federated Learning with Compression and Importance Sampling"
collection: publications
permalink: /publication/5GCS2
excerpt: 'Michał Grudzień, Grigory Malinovsky, Peter Richtárik'
date: 2023-06-05
venue: 'arXiv'
---

[PDF](https://arxiv.org/pdf/2302.09832.pdf), [Cite](https://grigory-malinovsky.github.io/files/5gcs-2.txt), [arXiv](https://arxiv.org/abs/2306.03240), [Federated Learning and Analytics in Practice: Algorithms, Systems, Applications, and Opportunities Workshop at ICML 2023](https://fl-icml2023.github.io) 

Abstract:
======
Federated Learning is a collaborative training framework that leverages heterogeneous data distributed across a vast number of clients. Since it is practically infeasible to request and process all clients during the aggregation step, partial participation must be supported. In this setting, the communication between the server and clients poses a major bottleneck. To reduce communication loads, there are two main approaches: compression and local steps. Recent work by Mishchenko et al. [2022] introduced the new ProxSkip method, which achieves an accelerated rate using the local steps technique. Follow-up works successfully combined local steps acceleration with partial participation [Grudzień et al., 2023, Condat et al. 2023] and gradient compression [Condat et al. [2022]. In this paper, we finally present a complete method for Federated Learning that incorporates all necessary ingredients: Local Training, Compression, and Partial Participation. We obtain state-of-the-art convergence guarantees in the considered setting. Moreover, we analyze the general sampling framework for partial participation and derive an importance sampling scheme, which leads to even better performance. We experimentally demonstrate the advantages of the proposed method in practice.
