---
title: Heavy-tailed Estimation is Easier than Adversarial Contamination
section: Original Papers
abstract: 'A large body of work in the statistics and computer science communities
  dating back to Huber (Huber, 1960) has led to the development of statistically and
  computationally efficient estimators robust to the presence of outliers in data.
  In the course of these developments, two particular outlier models have received
  significant attention: the adversarial and heavy-tailed contamination models. While
  the former models outliers as the result of a potentially malicious adversary inspecting
  and manipulating the data, the latter instead relaxes the assumptions on the distribution
  generating the data allowing outliers to naturally occur as part of the data generating
  process. In the first setting, the goal is to develop estimators robust to the largest
  fraction of outliers while in the second, one seeks estimators to combat the loss
  of \emph{statistical} efficiency caused by outliers, where the dependence on the
  failure probability is paramount. Surprisingly, despite these distinct motivations,
  the algorithmic approaches to both these settings have converged, prompting questions
  on the relationship between the corruption models. In this paper, we investigate
  and provide a principled explanation for this phenomenon. First, we prove that \emph{any}
  adversarially robust estimator is also resilient to heavy-tailed outliers for \emph{any}
  statistical estimation problem with i.i.d data. As a corollary, optimal adversarially
  robust estimators for mean estimation, linear regression, and covariance estimation
  are also optimal heavy-tailed estimators. Conversely, for arguably the simplest
  high-dimensional estimation task of mean estimation, we establish the existence
  of optimal heavy-tailed estimators whose application to the adversarial setting
  \emph{requires} any black-box reduction to remove \emph{almost all the outliers}
  in the data. Taken together, our results imply that heavy-tailed estimation is likely
  easier than adversarially robust estimation opening the door to novel algorithmic
  approaches bypassing the computational barriers inherent to the adversarial setting.
  Additionally, \emph{any} confidence intervals obtained for adversarially robust
  estimation also hold with high-probability. The proof of our reduction from heavy-tailed
  to adversarially robust estimation rests on the isoperimetry properties of the set
  of adversarially robust datasets. Conversely, we identify novel structural properties
  for samples drawn from a heavy-tailed distribution. We show that such a sample obeys
  a logarithmic tail-decay condition scaling with the target failure probability.
  This allows for a quantile-smoothed heavy-tailed estimator which \emph{requires
  arbitrarily large} stable subsets of the input data to succeed. In the process of
  analyzing this estimator, we also strengthen the analysis of algorithms utilized
  previously in the literature.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: cherapanamjeri25a
month: 0
tex_title: Heavy-tailed Estimation is Easier than Adversarial Contamination
firstpage: 1154
lastpage: 1184
page: 1154-1184
order: 1154
cycles: false
bibtex_author: Cherapanamjeri, Yeshwanth and Lee, Daniel
author:
- given: Yeshwanth
  family: Cherapanamjeri
- given: Daniel
  family: Lee
date: 2025-07-02
address:
container-title: Proceedings of Thirty Eighth Conference on Learning Theory
volume: '291'
genre: inproceedings
issued:
  date-parts:
  - 2025
  - 7
  - 2
pdf: https://raw.githubusercontent.com/mlresearch/v291/main/assets/cherapanamjeri25a/cherapanamjeri25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
