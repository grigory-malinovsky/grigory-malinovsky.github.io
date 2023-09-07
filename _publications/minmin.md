---
title: "An Optimal Algorithm for Strongly Convex Min-min Optimization"
collection: publications
permalink: /publication/minmin
excerpt: 'Dmitry Kovalev, Alexander Gasnikov, Grigory Malinovsky'
date: 2023-01-29
venue: 'arXiv'
---

[PDF](https://arxiv.org/pdf/2212.14439.pdf), [Cite](https://grigory-malinovsky.github.io/files/5gcs.txt), [arXiv](https://arxiv.org/abs/2212.14439), [The 26th International Conference on Artificial Intelligence and Statistics (AISTATS 2023)](https://aistats.org/aistats2023/accepted.html) 

Abstract:
======
In this paper we study the smooth strongly convex minimization problem $\min _x \min _y f(x, y)$. The existing optimal first-order methods require $\mathcal{O}\left(\sqrt{\max \left\{\kappa_x, \kappa_y\right\}}\right.$ log $\left.1 / \epsilon\right)$ of computations of both $\nabla_x f(x, y)$ and $\nabla_y f(x, y)$, where $\kappa_x$ and $\kappa_y$ are condition numbers with respect to variable blocks $x$ and $y$. We propose a new algorithm that only requires $\mathcal{O}\left(\sqrt{\kappa_x} \log 1 / \epsilon\right)$ of computations of $\nabla_x f(x, y)$ and $\mathcal{O}\left(\sqrt{\kappa_y} \log 1 / \epsilon\right)$ computations of $\nabla_y f(x, y)$. In some applications $\kappa_x \gg \kappa_y$, and computation of $\nabla_y f(x, y)$ is significantly cheaper than computation of $\nabla_x f(x, y)$. In this case, our algorithm substantially outperforms the existing state-of-the-art methods.
