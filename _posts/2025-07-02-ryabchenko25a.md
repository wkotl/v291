---
title: 'Capacity-Constrained Online Learning with Delays: Scheduling Frameworks and
  Regret Trade-offs'
section: Original Papers
abstract: 'We study online learning with oblivious losses and delays under a novel
  “capacity constraint” that limits how many past rounds can be tracked simultaneously
  for delayed feedback. Under “clairvoyance” (i.e., delay durations are revealed upfront
  each round) and/or “preemptibility” (i.e., we have ability to stop tracking previously
  chosen round feedback), we establish matching upper and lower bounds (up to logarithmic
  terms) on achievable regret, characterizing the “optimal capacity” needed to match
  the minimax rates of classical delayed online learning, which implicitly assume
  unlimited capacity.   Our algorithms achieve minimax-optimal regret across all capacity
  levels, with performance gracefully degrading under suboptimal capacity. For $K$
  actions and total delay $D$ over $T$ rounds, under clairvoyance and assuming capacity
  $C = \Omega(\log(T))$, we achieve regret $\widetilde{\Theta}(\sqrt{TK + DK/C + D\log(K)})$
  for bandits and $\widetilde{\Theta}(\sqrt{(D+T)\log(K)})$ for full-information feedback.
  When replacing clairvoyance with preemptibility, we require a known maximum delay
  bound $d_{\max}$, adding ${\widetilde{O}(d_{\max})}$ to the regret.   For fixed
  delays $d$ (i.e., $D=Td$), the minimax regret is $\Theta(\sqrt{TK(1+d/C)+Td\log(K)})$
  and the optimal capacity is $\Theta(\min\{K/\log(K),d\})$ in the bandit setting,
  while in the full-information feedback setting, the minimax regret is $\Theta(\sqrt{T(d+1)\log(K)})$
  and the optimal capacity is $\Theta(1)$. For round-dependent and fixed delays, our
  upper bounds are achieved using novel preemptive and non-preemptive scheduling policies,
  based on Pareto-distributed proxy delays, and batching techniques, respectively.
  Crucially, our work unifies delayed bandits, label-efficient learning, and online
  scheduling frameworks, demonstrating that robust online learning under delayed feedback
  is possible with surprisingly modest tracking capacity. '
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ryabchenko25a
month: 0
tex_title: 'Capacity-Constrained Online Learning with Delays: Scheduling Frameworks
  and Regret Trade-offs'
firstpage: 4973
lastpage: 5014
page: 4973-5014
order: 4973
cycles: false
bibtex_author: Ryabchenko, Alexander and Attias, Idan and Roy, Daniel M.
author:
- given: Alexander
  family: Ryabchenko
- given: Idan
  family: Attias
- given: Daniel M.
  family: Roy
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
pdf: https://raw.githubusercontent.com/mlresearch/v291/main/assets/ryabchenko25a/ryabchenko25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
