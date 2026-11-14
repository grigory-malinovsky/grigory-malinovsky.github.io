---
title: "First Provable Guarantees for Practical Private FL: Beyond Restrictive Assumptions"
collection: publications
permalink: /publication/Private-FL
excerpt: 'Egor Shulgin, Grigory Malinovsky, Sarit Khirirat, Peter Richtárik'
date: 2025-12-25
venue: 'The 17th Annual Workshop on Optimization for Machine Learning (OPT 2025, NeurIPS Workshop)'
materials:
  - label: "Paper"
    url: "https://arxiv.org/pdf/2512.21521"
  - label: "arXiv"
    url: "https://arxiv.org/abs/2512.21521"
  - label: "ICML 2025 workshop"
    url: "https://ttodlerfm.gitlab.io/accepted-papers/"
    title: "Tiny Titans: The next wave of On-Device Learning for Foundational Models (ICML Workshop 2025)"
  - label: "OPT 2025"
    url: "https://opt-ml.org/papers/2025/paper56.pdf"
    title: "OPT 2025 (NeurIPS Workshop)"
  - label: "Cite"
    url: "https://grigory-malinovsky.github.io/files/Private-FL.txt"
---

Abstract:
======
Federated Learning (FL) enables collaborative training on decentralized data. Differential privacy (DP) is crucial for FL, but current private methods often rely on unrealistic assumptions (e.g., bounded gradients or heterogeneity), hindering practical application. Existing works that relax these assumptions typically neglect practical FL features, including multiple local updates and partial client participation. We introduce Fed-$\alpha$-NormEC, the first differentially private FL framework providing provable convergence and DP guarantees under standard assumptions while fully supporting these practical features. Fed-$\alpha$-NormE integrates local updates (full and incremental gradient steps), separate server and client stepsizes, and, crucially, partial client participation, which is essential for real-world deployment and vital for privacy amplification. Our theoretical guarantees are corroborated by experiments on private deep learning tasks.
