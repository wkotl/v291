---
title: Learning Intersections of Two Margin Halfspaces under Factorizable Distributions
section: Original Papers
abstract: Learning intersections of halfspaces is a central problem in Computational
  Learning Theory. Even for just two halfspaces, it remains a major open question
  whether learning is possible in polynomial time with respect to the margin $\gamma$
  of the data points and their dimensionality $d$. The best-known algorithms run in
  quasi-polynomial time $d^{O( \log{1/\gamma} )}$, and it has been shown that this
  complexity is unavoidable for any algorithm relying solely on correlational statistical
  queries (CSQ). In this work, we introduce a novel algorithm that provably circumvents  the
  CSQ hardness barrier. Our approach applies to a broad class of  distributions satisfying
  a natural, previously studied, factorizability assumption. Factorizable distributions
  lie between the distribution-specific and distribution-free settings, and significantly
  extend previously known tractable cases. For these distributions,  we show that
  CSQ-based methods still require quasipolynomial time even for weak learning. Our
  main result is a learning algorithm for intersections of two margin halfspaces under
  factorizable distributions that  achieves $\text{poly}(d,1/\gamma)$  time by leveraging
  more general statistical queries (SQ). As a corollary, we establish a strong separation
  between CSQ and SQ for this fundamental PAC learning problem.  Our main result is
  grounded in a rigorous analysis utilizing a novel duality framework that characterizes
  the moment tensor structure induced by the marginal distributions. Building on these
  structural insights, our learning algorithm combines a refined variant of Jennrich’s
  Algorithm with PCA over random projections of the moment tensor, along with a gradient-descent-based
  non-convex optimization framework.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: diakonikolas25a
month: 0
tex_title: Learning Intersections of Two Margin Halfspaces under Factorizable Distributions
firstpage: 1472
lastpage: 1530
page: 1472-1530
order: 1472
cycles: false
bibtex_author: Diakonikolas, Ilias and Mingchen, Ma and Lisheng, Ren and Christos,
  Tzamos
author:
- given: Ilias
  family: Diakonikolas
- given: Ma
  family: Mingchen
- given: Ren
  family: Lisheng
- given: Tzamos
  family: Christos
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
pdf: https://raw.githubusercontent.com/mlresearch/v291/main/assets/diakonikolas25a/diakonikolas25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
