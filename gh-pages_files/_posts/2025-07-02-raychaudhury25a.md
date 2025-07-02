---
title: Metric Clustering and Graph Optimization Problems using Weak Comparison Oracles
section: Original Papers
abstract: 'Traditional clustering methods assume that precise pairwise distances for
  the input data are readily available. However, this assumption is often impractical
  in real-world scenarios where data points cannot be measured accurately. For instance,
  machine learning-based techniques for estimating distances may fail when the dataset
  consists of images, videos, or natural language. This paper studies clustering and
  graph problems in settings where direct access to pairwise distances between all
  pairs is expensive.  We adopt oracle-based methods as defined by Galhotra et al.
  (2024), focusing on two types of oracles: the quadruplet oracle, a weak and inexpensive
  comparator that answers binary queries of the form "Is A closer to B or C closer
  to D?" and the distance oracle, a stronger but costlier oracle that returns exact
  pairwise distances. The quadruplet oracle can be implemented via crowdsourcing,
  trained classifiers, or other predictive models. As these sources are often unreliable,
  the oracle’s responses may be noisy; we consider both probabilistic and adversarial
  noise models.  Consider a finite metric space $\Sigma=(\mathcal{V},d)$ of size $|\mathcal{V}|=n$
  that supports the quadruplet and the distance oracle. When the input dataset has
  low intrinsic (doubling) dimension, for each of the $k$-center, $k$-median, and
  $k$-means clustering problem on $\mathcal{V}$, we design constant approximation
  algorithms that perform  $\widetilde{O}(n+k^2)$ calls to the quadruplet oracle and
  $\widetilde{O}(1)$ calls to the distance oracle in both noise models. For general
  metric spaces, our algorithms achieve constant approximation while making $\widetilde{O}(nk)$
  calls to the quadruplet oracle and $\widetilde{O}(1)$ calls to the distance oracle.
  In all cases, we improve the quadruplet oracle query complexity by a factor of $k$
  and the distance oracle call complexity by a factor of $k^2$ compared to Galhotra
  et al. (2024).  Furthermore, in low dimensional settings, if the spread of the input
  data is polynomially bounded, we construct a data structure performing $\widetilde{O}(n)$
  queries to the quadruplet oracle and $\widetilde{O}(1)$ queries to the distance
  oracle, such that given any query pair of vertices $(u,v)\in \mathcal{V}\times \mathcal{V}$,
  it approximates the distance $d(u,v)$ without using any oracle queries. Once the
  data structure is constructed, we can emulate standard algorithms for various graph
  problems on $\Sigma$ without additional oracle queries.  In summary, our results
  show that access to a noisy pairwise ranker for distances is to sufficient to efficiently
  solve a large class of problems while almost entirely bypassing exact distance computations. '
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: raychaudhury25a
month: 0
tex_title: Metric Clustering and Graph Optimization Problems using Weak Comparison
  Oracles
firstpage: 4777
lastpage: 4830
page: 4777-4830
order: 4777
cycles: false
bibtex_author: Raychaudhury, Rahul and Li, Wen-Zhi and Das, Syamantak and Galhotra,
  Sainyam and Sintos, Stavros
author:
- given: Rahul
  family: Raychaudhury
- given: Wen-Zhi
  family: Li
- given: Syamantak
  family: Das
- given: Sainyam
  family: Galhotra
- given: Stavros
  family: Sintos
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
pdf: https://raw.githubusercontent.com/mlresearch/v291/main/assets/raychaudhury25a/raychaudhury25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
