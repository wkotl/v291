---
title: The Space Complexity of Learning-Unlearning Algorithms (extended abstract)
section: Original Papers
abstract: We study the memory complexity of machine unlearning algorithms that provide
  strong data deletion guarantees to the users. Formally, consider an algorithm for
  a particular learning task that initially receives a training dataset. Then, after
  learning, it receives data deletion requests from a subset of users (of arbitrary
  size), and the goal of unlearning is to perform the task as if the learner never
  received the data of deleted users. In this paper, we ask how many bits of storage
  are needed to be able to complete certain training samples, at a later time. We
  focus on the task of realizability testing, where the goal is to check whether the
  remaining training samples are realizable within a given hypothesis class $\mathcal{H}$.
  Toward that end, we first provide a negative result showing that the VC dimension,
  a well-known combinatorial property of $\mathcal{H}$ that characterizes the amount
  of information needed for learning and representing the ERM hypothesis in the standard
  PAC learning task—is not a characterization of the space complexity of unlearning.
  In particular, we provide a hypothesis class with constant VC dimension (and Littlestone
  dimension), but for which any unlearning algorithm for realizability testing needs
  to store $\Omega(n)$ bits, where $n$ denotes the size of the initial training dataset.
  In fact, we provide a stronger separation by showing that for any hypothesis class
  $\mathcal{H}$, the amount of information that the learner needs to store, so as
  to perform unlearning later, is lower bounded by the Eluder dimension of $\mathcal{H}$,
  a combinatorial notion always larger than the VC dimension. We complement the lower
  bound with an upper bound in terms of the star number of the underlying hypothesis
  class, albeit in a stronger ticketed memory model proposed by Ghoroi et al. (2023).
  We show that for any class $\mathcal{H}$ with bounded star number, there exists
  a ticketed scheme that uses only $\tilde{O}(\text{StarNo}(\mathcal{H}))$ many bits
  of storage and these many tickets. Since, the star number for a hypothesis class
  is never larger than its Eluder dimension, our work highlights a fundamental separation
  between central and ticketed memory models for machine unlearning. Lastly, we consider
  the setting where the number of deletions is bounded and show that in contrast to
  the unbounded setting, there exist unlearning schemes with sublinear (in $n$) storage
  for hypothesis classes with bounded hollow star number, a notion of complexity that
  is always smaller than the star number and the Eluder dimension.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: cherapanamjeri25b
month: 0
tex_title: The Space Complexity of Learning-Unlearning Algorithms (extended abstract)
firstpage: 1185
lastpage: 1193
page: 1185-1193
order: 1185
cycles: false
bibtex_author: Cherapanamjeri, Yeshwanth and Garg, Sumegba and Rajaraman, Nived and
  Sekhari, Ayush and Shetty, Abhishek
author:
- given: Yeshwanth
  family: Cherapanamjeri
- given: Sumegba
  family: Garg
- given: Nived
  family: Rajaraman
- given: Ayush
  family: Sekhari
- given: Abhishek
  family: Shetty
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
pdf: https://raw.githubusercontent.com/mlresearch/v291/main/assets/cherapanamjeri25b/cherapanamjeri25b.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
