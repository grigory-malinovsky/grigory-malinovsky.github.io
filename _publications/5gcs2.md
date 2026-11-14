---
title: "Improving Accelerated Federated Learning with Compression and Importance Sampling"
collection: publications
permalink: /publication/5GCS2
excerpt: 'Michał Grudzień, Grigory Malinovsky, Peter Richtárik'
date: 2025-10-17
venue: "International Conference on Computational Optimization (ICOMP 2025, Oral)"
materials:
  - label: "Paper"
    url: "https://arxiv.org/pdf/2306.03240.pdf"
  - label: "arXiv"
    url: "https://arxiv.org/abs/2306.03240"
  - label: "ICML 2023 workshop"
    url: "https://fl-icml2023.github.io"
    title: "Federated Learning and Analytics in Practice: Algorithms, Systems, Applications, and Opportunities Workshop at ICML 2023"
  - label: "ICOMP 2025"
    url: "https://icomp.cc"
    title: "ICOMP 2025 (Oral)"
  - label: "Cite"
    url: "https://grigory-malinovsky.github.io/files/5gcs-2.txt"
---

Abstract:
======
Federated Learning is a collaborative training framework that leverages heterogeneous data distributed across a vast number of clients. Since it is practically infeasible to request and process all clients during the aggregation step, partial participation must be supported. In this setting, the communication between the server and clients poses a major bottleneck. To reduce communication loads, there are two main approaches: compression and local steps. Recent work by Mishchenko et al. [2022] introduced the new ProxSkip method, which achieves an accelerated rate using the local steps technique. Follow-up works successfully combined local steps acceleration with partial participation [Grudzień et al., 2023, Condat et al. 2023] and gradient compression [Condat et al. [2022]. In this paper, we finally present a complete method for Federated Learning that incorporates all necessary ingredients: Local Training, Compression, and Partial Participation. We obtain state-of-the-art convergence guarantees in the considered setting. Moreover, we analyze the general sampling framework for partial participation and derive an importance sampling scheme, which leads to even better performance. We experimentally demonstrate the advantages of the proposed method in practice.
