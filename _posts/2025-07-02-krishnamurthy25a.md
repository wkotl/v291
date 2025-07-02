---
title: The Role of Environment Access in Agnostic Reinforcement Learning (Extended
  Abstract)
section: Original Papers
abstract: 'We study Reinforcement Learning (RL) in environments with large state spaces,
  where function approximation is required for sample-efficient learning. Departing
  from a long history of prior work, we consider the weakest possible form of function
  approximation, called agnostic policy learning, where the learner seeks to find
  the best policy in a given class $\Pi$, with no guarantee that $\Pi$ contains an
  optimal policy for the underlying task. Although it is known that sample-efficient
  agnostic policy learning is not possible in the standard online RL setting without
  further assumptions, we investigate the extent to which this can be overcome with
  stronger forms of access to the environment. Specifically:  1) We show that even
  with a strong function approximation assumption called \emph{policy completeness},
  and \emph{generative access}—perhaps the strongest possible access to the MDP—policy
  learning methods cannot achieve sample complexity guarantees that scale with the
  intrinsic complexity of exploration, as measured via the \emph{coverability coefficient}[XFB+22]
  of the MDP. This resolves an open problem posed by [JLR+23] and shows, in a strong,
  information-theoretic sense, that policy learning methods cannot explore. 2) We
  study the $\mu$-reset setting, where the learner can roll out from an exploratory
  reset distribution $\mu$, and investigate whether error amplification can be controlled
  without policy completeness (which is required for classical results of PSDP [BKSN03]
  and CPI [KL02]). We show that agnostic policy learning is information-theoretically
  impossible. We also show algorithm-specific lower bounds for PSDP and CPI under
  the weaker condition of \emph{policy class realizability}. 3) In light of these
  lower bounds, we introduce a new model of access called \emph{hybrid resets}, which
  subsumes both local simulators (which is weaker than generative access) and $\mu$-resets.
  We show that under hybrid resets, and when the reset distribution satisfies \emph{pushforward
  concentrability} [XJ21], sample-efficient policy learning is possible in Block MDPs
  [JKA+17, DKJ+19] via a new algorithm.  Since all of our lower bound constructions
  are Block MDPs, this indicates the significant power of hybrid reset access in agnostic
  policy learning. On a technical level, we introduce a new algorithmic tool called
  a \emph{policy emulator} that allows us to efficiently evaluate various policies
  within a  large class $\Pi$. Informally speaking, a policy emulator is the “minimal
  object” useful for solving policy learning. Instead of learning the Block MDP in
  a traditional model-based sense (which would require samples scaling with the observation
  space size), our algorithm leverages hybrid resets to construct a policy emulator
  in a statistically efficient manner. Taken together, our results reveal intriguing
  interplays between function approximation and environment access in RL. Extended
  abstract. Full version appears as \href{https://arxiv.org/abs/2504.05405}{[arXiv:2504.05405,
  v1]}. Authors are listed in alphabetical order of their last names. '
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: krishnamurthy25a
month: 0
tex_title: The Role of Environment Access in Agnostic Reinforcement Learning (Extended
  Abstract)
firstpage: 3405
lastpage: 3406
page: 3405-3406
order: 3405
cycles: false
bibtex_author: Krishnamurthy, Akshay and Li, Gene and Sekhari, Ayush
author:
- given: Akshay
  family: Krishnamurthy
- given: Gene
  family: Li
- given: Ayush
  family: Sekhari
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
pdf: https://raw.githubusercontent.com/mlresearch/v291/main/assets/krishnamurthy25a/krishnamurthy25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
