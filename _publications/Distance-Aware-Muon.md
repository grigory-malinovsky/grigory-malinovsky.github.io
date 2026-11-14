---
title: "Distance-Aware Muon: Adaptive Step Scaling for Normalized Optimization"
collection: publications
permalink: /publication/Distance-Aware-Muon
excerpt: 'Yury Demidovich, Abhishek Chakraborty, Grigory Malinovsky, Angelia Nedić, Peter Richtárik'
date: 2026-05-18
venue: 'arXiv'
materials:
  - label: "Paper"
    url: "https://arxiv.org/pdf/2605.18999"
  - label: "arXiv"
    url: "https://arxiv.org/abs/2605.18999"
  - label: "Cite"
    url: "https://grigory-malinovsky.github.io/files/Distance-Aware-Muon.txt"
---

Abstract:
======
Muon and related normalized optimizers decouple the choice of update direction from the choice of step scale, but their practical performance remains sensitive to the scale of the normalized step. We study adaptive scaling rules for Muon in general norm geometries and develop three complementary algorithms. For smooth non-convex objectives, we introduce Distance-Adaptive Muon, whose trust-region radius is set from the radius explored by the trajectory, and prove a stationarity guarantee under a bounded-trajectory assumption. We then turn to star-convex objectives, a tractable model of the favorable global geometry often used to reason about the empirical loss landscapes of deep neural networks, where objective-gap guarantees are possible. In this setting, we first introduce Scale-Calibrated Muon, which keeps Muon's exponential moving average but sets the step length from a local descent certificate computed from the current gradient and momentum. For this method, we prove a last-iterate O(1/T) objective-gap bound under a bounded initial sublevel-set assumption, where the corresponding radius parameter appears only in the analysis and not in the algorithm. Finally, we develop Distance-Free Muon, a recentered trust-region method that uses a scalar distance certificate and a majorized one-dimensional search to select the trust-region radius without requiring the unknown distance from the initialization to a global minimizer. Experiments on Transformer language modeling (GPT-124M/WikiText-103) and image classification (ViT-Tiny/CIFAR-100) show that the proposed adaptive scaling rules reduce sensitivity to manual scale tuning and match or improve tuned fixed-scale Muon baselines under the tested budgets.
