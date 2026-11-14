---
title: "An Optimal Algorithm for Strongly Convex Min-min Optimization"
collection: publications
permalink: /publication/minmin
excerpt: 'Dmitry Kovalev, Alexander Gasnikov, Grigory Malinovsky'
date: 2025-07-22
venue: "The 41st Conference on Uncertainty in Artificial Intelligence (UAI 2025)"
materials:
  - label: Paper
    url: "https://arxiv.org/pdf/2212.14439.pdf"
  - label: Cite
    url: "https://grigory-malinovsky.github.io/files/minmin.txt"
---

[arXiv](https://arxiv.org/abs/2212.14439), [UAI 2025](https://www.auai.org/uai2025/)

Abstract:
======
In this paper we study the smooth strongly convex minimization problem $\min _x \min _y f(x, y)$. The existing optimal first-order methods require $\mathcal{O}\left(\sqrt{\max \left( \kappa_x, \kappa_y\right) }\log \frac{ 1} { \epsilon} \right)$ of computations of both $\nabla_x f(x, y)$ and $\nabla_y f(x, y)$, where $\kappa_x$ and $\kappa_y$ are condition numbers with respect to variable blocks $x$ and $y$. We propose a new algorithm that only requires $\mathcal{O}\left(\sqrt{\kappa_x} \log 1 / \epsilon\right)$ of computations of $\nabla_x f(x, y)$ and $\mathcal{O}\left(\sqrt{\kappa_y} \log 1 / \epsilon\right)$ computations of $\nabla_y f(x, y)$. In some applications $\kappa_x \gg \kappa_y$, and computation of $\nabla_y f(x, y)$ is significantly cheaper than computation of $\nabla_x f(x, y)$. In this case, our algorithm substantially outperforms the existing state-of-the-art methods.
