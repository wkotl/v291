---
title: How to safely discard features based on aggregate SHAP values
section: Original Papers
abstract: 'SHAP is one of the most popular \textit{local} feature-attribution methods.
  Given a function $f$ and an input $x \in \mathbb{R}^d$, it quantifies each feature’s
  contribution to $f(x)$. Recently, SHAP has been increasingly used for \textit{global}
  insights: practitioners average the absolute SHAP values over many data points to
  compute global feature importance scores, which are then used to discard “unimportant”
  features. % In this work, we investigate the soundness of this practice by asking
  whether small aggregate SHAP values necessarily imply that the corresponding feature
  does not affect the function. Unfortunately, the answer is no: even if the $i$-th
  SHAP value equals $0$ on the entire data support, there exist functions that clearly
  depend on Feature $i$. The issue is that computing SHAP values involves evaluating
  $f$ on points outside of the data support, where $f$ can be strategically designed
  to mask its dependence on Feature $i$. % To address this, we propose to aggregate
  SHAP values over the \textit{extended} support, which is the product of the marginals
  of the underlying distribution. With this modification, we show that a small aggregate
  SHAP value implies that we can safely discard the corresponding feature. % We then
  extend our results to KernelSHAP, the most popular method to approximate SHAP values
  in practice. We show that if KernelSHAP is computed over the extended distribution,
  a small aggregate KernelSHAP value justifies feature removal. This result holds
  independently of whether KernelSHAP accurately approximates true SHAP values, making
  it one of the first theoretical results to characterize the KernelSHAP algorithm
  itself. Our findings have both theoretical and practical implications. We introduce
  the "Shapley Lie algebra", which offers algebraic insights that may enable a deeper
  investigation of SHAP and we show that a simple preprocessing step – randomly permuting
  each column of the data matrix – enables safely discarding features based on aggregate
  SHAP and KernelSHAP values.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bhattacharjee25a
month: 0
tex_title: How to safely discard features based on aggregate SHAP values
firstpage: 280
lastpage: 314
page: 280-314
order: 280
cycles: false
bibtex_author: Bhattacharjee, Robi and Frohnapfel, Karolin and von Luxburg, Ulrike
author:
- given: Robi
  family: Bhattacharjee
- given: Karolin
  family: Frohnapfel
- given: Ulrike
  family: Luxburg
  prefix: von
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
pdf: https://raw.githubusercontent.com/mlresearch/v291/main/assets/bhattacharjee25a/bhattacharjee25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
