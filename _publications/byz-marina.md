---
title: "Byzantine Robustness and Partial Participation Can Be Achieved Simultaneously: Just Clip Gradient Differences"
collection: publications
permalink: /publication/Byz-MARINA-PP
excerpt: 'Grigory Malinovsky, Peter Richtárik', Samuel Horváth, Eduard Gorbunov 
date: 2023-23-11
venue: 'arXiv'
---

[PDF](https://arxiv.org/pdf/2306.03240.pdf), [Cite](https://grigory-malinovsky.github.io/files/5gcs-2.txt), [arXiv](https://arxiv.org/abs/2306.03240), [Federated Learning and Analytics in Practice: Algorithms, Systems, Applications, and Opportunities Workshop at ICML 2023](https://fl-icml2023.github.io) 

Abstract:
======
Distributed learning has emerged as a leading paradigm for training large machine learning models. However, in real-world scenarios, participants may be unreliable or malicious, posing a significant challenge to the integrity and accuracy of the trained models. Byzantine fault tolerance mechanisms have been proposed to address these issues, but they often assume full participation from all clients, which is not always practical due to the unavailability of some clients or communication constraints. In our work, we propose the first distributed method with client sampling and provable tolerance to Byzantine workers. The key idea behind the developed method is the use of gradient clipping to control stochastic gradient differences in recursive variance reduction. This allows us to bound the potential harm caused by Byzantine workers, even during iterations when all sampled clients are Byzantine. Furthermore, we incorporate communication compression into the method to enhance communication efficiency. Under general assumptions, we prove convergence rates for the proposed method that match the existing state-of-the-art (SOTA) theoretical results. We also propose a heuristic on adjusting any Byzantine-robust method to a partial participation scenario via clipping.
