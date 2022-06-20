---
title: "Federated Random Reshuffling with Compression and Variance Reduction"
collection: publications
permalink: /publication/RR-comp-it
excerpt: 'Grigory Malinovsky, Peter Richtárik'
date: 2022-02-09
venue: 'arXiv'
---

[PDF](https://arxiv.org/pdf/2205.03914.pdf), [Cite](https://grigory-malinovsky.github.io/files/averaged_hb.txt), [arXiv](https://arxiv.org/abs/2205.03914), [International Workshop on Federated Learning for User Privacy and Data Confidentiality 
in Conjunction with ICML 2021 (FL-ICML'21)](https://fl-icml.github.io/2021/papers/FL-ICML21_paper_34.pdf) 

Abstract:
======
Random Reshuffling (RR), which is a variant of Stochastic Gradient Descent (SGD) employing sampling without replacement, is an immensely popular method for training supervised machine learning models via empirical risk minimization. Due to its superior practical performance, it is embedded and often set as default in standard machine learning software. Under the name FedRR, this method was recently shown to be applicable to federated learning (Mishchenko et al.,2021), with superior performance when compared to common baselines such as Local SGD. Inspired by this development, we design three new algorithms to improve FedRR further: compressed FedRR and two variance reduced extensions: one for taming the variance coming from shuffling and the other for taming the variance due to compression. The variance reduction mechanism for compression allows us to eliminate dependence on the compression parameter, and applying additional controlled linear perturbations for Random Reshuffling, introduced by Malinovsky et al.(2021) helps to eliminate variance at the optimum. We provide the first analysis of compressed local methods under standard assumptions without bounded gradient assumptions and for heterogeneous data, overcoming the limitations of the compression operator. We corroborate our theoretical results with experiments on synthetic and real data sets.
