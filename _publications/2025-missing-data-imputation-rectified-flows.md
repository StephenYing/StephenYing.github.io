---
title: "Missing Data Imputation by Reducing Mutual Information with Rectified Flows"
collection: publications
category: conferences
permalink: /publication/2025-missing-data-imputation-rectified-flows
excerpt: 'This paper introduces a novel iterative method for missing data imputation that sequentially reduces the mutual information between data and their corresponding missing mask.'
date: 2025-01-01
venue: "arXiv preprint"
paperurl: "https://arxiv.org/abs/2505.11749"
bibtexurl: "https://arxiv.org/bibtex/2505.11749"
citation: 'Yu, Jiahao, Qizhen Ying, Leyang Wang, Ziyue Jiang, and Song Liu. "Missing Data Imputation by Reducing Mutual Information with Rectified Flows." arXiv preprint arXiv:2505.11749 (2025).'
---

This paper introduces a novel iterative method for missing data imputation that sequentially reduces the mutual information between data and their corresponding missing mask. Inspired by GAN-based approaches, which train generators to decrease the predictability of missingness patterns, our method explicitly targets the reduction of mutual information.

Specifically, our algorithm iteratively minimizes the KL divergence between the joint distribution of the imputed data and missing mask, and the product of their marginals from the previous iteration. We show that the optimal imputation under this framework corresponds to solving an ODE, whose velocity field minimizes a rectified flow training objective. 

We further illustrate that some existing imputation techniques can be interpreted as approximate special cases of our mutual-information-reducing framework. Comprehensive experiments on synthetic and real-world datasets validate the efficacy of our proposed approach, demonstrating superior imputation performance.