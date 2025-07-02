---
title: Market Making without Regret
section: Original Papers
abstract: We consider a sequential decision-making setting where, at every round $t$,
  the learner (a market maker) posts a bid price $B_t$ and an ask price $A_t$ to an
  incoming trader (the taker) with a private valuation for some asset. If the trader’s
  valuation is lower than the bid price, or higher than the ask price, then a trade
  (sell or buy) occurs. Letting $M_t$ be the market price (observed only at the end
  of round $t$), the maker’s utility is $M_t-B_t$ if the maker bought the asset, it
  is $A_t-M_t$ if they sold it, and it is $0$ if no trade occurred. We characterize
  the maker’s regret with respect to the best fixed choice of bid and ask pairs under
  a variety of assumptions (adversarial, i.i.d., and their variants) on the sequence
  of market prices and valuations.  Our upper bound analysis unveils an intriguing
  connection relating market making to first-price auctions and dynamic pricing. Our
  main technical contribution is a lower bound for the i.i.d. case with Lipschitz
  distributions and independence between market prices and takers’ valuations. The
  difficulty in the analysis stems from a unique relationship between the reward and
  feedback functions that allows learning algorithms to trade off reward for information
  in a continuous way.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: cesa-bianchi25a
month: 0
tex_title: Market Making without Regret
firstpage: 799
lastpage: 837
page: 799-837
order: 799
cycles: false
bibtex_author: Cesa-Bianchi, Nicol\`{o} and Cesari, Tommaso and Colomboni, Roberto
  and Foscari, Luigi and Pathak, Vinayak
author:
- given: Nicolò
  family: Cesa-Bianchi
- given: Tommaso
  family: Cesari
- given: Roberto
  family: Colomboni
- given: Luigi
  family: Foscari
- given: Vinayak
  family: Pathak
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
pdf: https://raw.githubusercontent.com/mlresearch/v291/main/assets/cesa-bianchi25a/cesa-bianchi25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
