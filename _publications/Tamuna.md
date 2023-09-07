---
title: "TAMUNA: Doubly Accelerated Federated Learning with Local Training, Compression, and Partial Participation"
collection: publications
permalink: /publication/5GCS
excerpt: 'Laurent Condat, Ivan Agarský, Grigory Malinovsky, Peter Richtárik'
date: 2023-02-24
venue: 'arXiv'
---

[PDF](https://arxiv.org/pdf/2302.09832.pdf), [Cite](https://grigory-malinovsky.github.io/files/5gcs.txt), [arXiv](https://arxiv.org/abs/2302.09832)

Abstract:
======
In federated learning, a large number of users collaborate to learn a global model. They alternate local computations and communication with a distant server. Communication, which can be slow and costly, is the main bottleneck in this setting. In addition to communication-efficiency, a robust algorithm should allow for partial participation, the desirable feature that not all clients need to participate to every round of the training process. To reduce the communication load and therefore accelerate distributed gradient descent, two strategies are popular: 1) communicate less frequently; that is, perform several iterations of local computations between the communication rounds; and 2) communicate compressed information instead of full-dimensional vectors. We propose TAMUNA, the first algorithm for distributed optimization and federated learning, which harnesses these two strategies jointly and allows for partial participation. TAMUNA converges linearly to an exact solution in the strongly convex setting, with a doubly accelerated rate: it provably benefits from the two acceleration mechanisms provided by local training and compression, namely a better dependency on the condition number of the functions and on the model dimension, respectively.
