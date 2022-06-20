---
title: "Server-Side Stepsizes and Sampling Without Replacement Provably Help in Federated Optimization"
collection: publications
permalink: /publication/FedRR-two-stepsizes
excerpt: 'Grigory Malinovsky, Konstantin Mishchenko, Peter Richtárik'
date: 2022-01-26 
venue: 'arXiv'
---
[PDF](https://arxiv.org/pdf/2201.11066), [Cite](https://grigory-malinovsky.github.io/files/RR-VR.txt), [arXiv](https://arxiv.org/abs/2201.11066), [OPT2021: 13th Annual Workshop on Optimization for Machine Learning](https://opt-ml.org/papers/2021/paper39.pdf) 


Abstract:
======
We present a theoretical study of server-side optimization in federated learning. Our results are the first to show that the widely popular heuristic of scaling the client updates with an extra parameter is very useful in the context of Federated Averaging (FedAvg) with local passes over the client data. Each local pass is performed without replacement using Random Reshuffling, which is a key reason we can show improved complexities. In particular, we prove that whenever the local stepsizes are small, and the update direction is given by FedAvg in conjunction with Random Reshuffling over all clients, one can take a big leap in the obtained direction and improve rates for convex, strongly convex, and non-convex objectives. In particular, in non-convex regime we get an enhancement of the rate of convergence from $\mathcal{O}(\varepsilon^{-3}) \text{ to } \mathcal{O}(\varepsilon^{-2})$. This result is new even for Random Reshuffling performed on a single node. In contrast, if the local stepsizes are large, we prove that the noise of client sampling can be controlled by using a small server-side stepsize. To the best of our knowledge, this is the first time that local steps provably help to overcome the communication bottleneck. Together, our results on the advantage of large and small server-side stepsizes give a formal justification for the practice of adaptive server-side optimization in federated learning. Moreover, we consider a variant of our algorithm that supports partial client participation, which makes the method more practical.




