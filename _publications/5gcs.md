---
title: "Can 5th Generation Local Training Methods Support Client Sampling? Yes!"
collection: publications
permalink: /publication/5GCS
excerpt: 'Michał Grudzień, Grigory Malinovsky, Peter Richtárik'
date: 2022-12-29
venue: 'The 26th International Conference on Artificial Intelligence and Statistics (AISTATS 2023)'
---

[PDF](https://arxiv.org/abs/2212.14370.pdf), [Cite](https://grigory-malinovsky.github.io/files/averaged_hb.txt), [arXiv](https://arxiv.org/abs/2212.14370), [Computer Research and Modeling](http://crm-en.ics.org.ru/journal/article/3184/) 

Abstract:
======
The celebrated FedAvg algorithm of McMahan et al. (2017) is based on three components: client sampling (CS), data sampling (DS) and local training (LT). While the first two are reasonably well understood, the third component, whose role is to reduce the number of communication rounds needed to train the model, resisted all attempts at a satisfactory theoretical explanation. Malinovsky et al. (2022) identified four distinct generations of LT methods based on the quality of the provided theoretical communication complexity guarantees. Despite a lot of progress in this area, none of the existing works were able to show that it is theoretically better to employ multiple local gradient-type steps (i.e., to engage in LT) than to rely on a single local gradient-type step only in the important heterogeneous data regime. In a recent breakthrough embodied in their ProxSkip method and its theoretical analysis, Mishchenko et al. (2022) showed that LT indeed leads to provable communication acceleration for arbitrarily heterogeneous data, thus jump-starting the 5th generation of LT methods. However, while these latest generation LT methods are compatible with DS, none of them support CS. We resolve this open problem in the affirmative. In order to do so, we had to base our algorithmic development on new algorithmic and theoretical foundations.
