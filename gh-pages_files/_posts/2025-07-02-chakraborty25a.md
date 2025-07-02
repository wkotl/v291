---
title: 'Towards Fair Representation: Clustering and Consensus'
section: Original Papers
abstract: Consensus clustering, a fundamental task in machine learning and data analysis,
  aims to aggregate multiple input clusterings of a dataset, potentially based on
  different non-sensitive attributes, into a single clustering that best represents
  the collective structure of the data. In this work, we study this fundamental problem
  through the lens of fair clustering, as introduced by Chierichetti et al. [NeurIPS’17],
  which incorporates the disparate impact doctrine to ensure proportional representation
  of each protected group in the dataset within every cluster. Our objective is to
  find a consensus clustering that is not only representative but also fair with respect
  to specific protected attributes. To the best of our knowledge, we are the first
  to address this problem and provide a constant-factor approximation. As part of
  our investigation, we examine how to minimally modify an existing clustering to
  enforce fairness – an essential postprocessing step in many clustering applications
  that require fair representation. We develop an optimal algorithm for datasets with
  equal group representation and near-linear time constant factor approximation algorithms
  for more general scenarios with different proportions of two group sizes. We complement
  our approximation result by showing that the problem is NP-hard for two unequal-sized
  groups. Given the fundamental nature of this problem, we believe our results on
  Closest Fair Clustering could have broader implications for other clustering problems,
  particularly those for which no prior approximation guarantees exist for their fair
  variants.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chakraborty25a
month: 0
tex_title: 'Towards Fair Representation: Clustering and Consensus'
firstpage: 838
lastpage: 853
page: 838-853
order: 838
cycles: false
bibtex_author: Chakraborty, Diptarka and Chatterjee, Kushagra and Das, Debarati and
  Nguyen, Tien Long and Nobahari, Romina
author:
- given: Diptarka
  family: Chakraborty
- given: Kushagra
  family: Chatterjee
- given: Debarati
  family: Das
- given: Tien Long
  family: Nguyen
- given: Romina
  family: Nobahari
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
pdf: https://raw.githubusercontent.com/mlresearch/v291/main/assets/chakraborty25a/chakraborty25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
