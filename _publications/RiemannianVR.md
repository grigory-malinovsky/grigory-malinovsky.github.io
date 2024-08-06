---
title: "Streamlining in the Riemannian Realm: Efficient Riemannian Optimization with Loopless Variance Reduction"
collection: publications
permalink: /publication/RiemannianVR
excerpt: 'Yury Demidovich, Grigory Malinovsky, Peter Richtárik'
date: 2024-03-11
venue: 'arXiv'
---
[PDF](https://arxiv.org/pdf/2403.06677.pdf), [Cite](https://grigory-malinovsky.github.io/files/RiemannianVR.txt), [arXiv](https://arxiv.org/abs/2403.06677)

Abstract:
======
In this study, we investigate stochastic optimization on Riemannian manifolds, focusing on the crucial variance reduction mechanism used in both Euclidean and Riemannian settings. Riemannian variance-reduced methods usually involve a double-loop structure, computing a full gradient at the start of each loop. Determining the optimal inner loop length is challenging in practice, as it depends on strong convexity or smoothness constants, which are often unknown or hard to estimate. Motivated by Euclidean methods, we introduce the Riemannian Loopless SVRG (R-LSVRG) and PAGE (R-PAGE) methods. These methods replace the outer loop with probabilistic gradient computation triggered by a coin flip in each iteration, ensuring simpler proofs, efficient hyperparameter selection, and sharp convergence guarantees. Using R-PAGE as a framework for non-convex Riemannian optimization, we demonstrate its applicability to various important settings. For example, we derive Riemannian MARINA (R-MARINA) for distributed settings with communication compression, providing the best theoretical communication complexity guarantees for non-convex distributed optimization over Riemannian manifolds. Experimental results support our theoretical findings.

