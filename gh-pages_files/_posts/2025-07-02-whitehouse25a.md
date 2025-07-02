---
title: Orthogonal Causal Calibration (Extended Abstract)
section: Original Papers
abstract: 'Estimates of heterogeneous treatment effects such as conditional average
  treatment effects (CATEs) and conditional quantile treatment effects (CQTEs) play
  an important role in real-world decision making. Given this importance, one should
  ensure these estimators are calibrated. While there is a rich literature on calibrating
  estimators of non-causal parameters, very few methods have been derived for calibrating
  estimators of causal parameters, or more generally estimators of quantities involving
  nuisance parameters.  In this work, we develop general algorithms for reducing the
  task of causal calibration to that of calibrating a standard (non-causal) predictive
  model. Throughout, we study a notion of calibration defined with respect to an arbitrary,
  nuisance-dependent loss $\ell$, under which we say an estimator $\theta$ is calibrated
  if its predictions cannot be changed on any level set to decrease loss. For losses
  $\ell$ satisfying a condition called universal orthogonality, we present a simple
  algorithm that transforms partially-observed data into generalized pseudo-outcomes
  and applies any off-the-shelf calibration procedure. For losses $\ell$ satisfying
  a weaker assumption called conditional orthogonality, we provide a similar sample
  splitting algorithm the performs empirical risk minimization over an appropriately
  defined class of functions. Convergence of both algorithms follows from a generic,
  two term upper bound of the calibration error of any model that decouples the error
  in estimating unknown nuisance parameters from the calibration error in a hypothetical
  world where the learned nuisances are true. We demonstrate the practical applicability
  of our results in experiments on both observational and synthetic data. Our results
  are exceedingly general, showing that essentially any existing calibration algorithm
  can be used in causal settings, with additional loss only arising from errors in
  nuisance estimation. '
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: whitehouse25a
month: 0
tex_title: Orthogonal Causal Calibration (Extended Abstract)
firstpage: 5712
lastpage: 5713
page: 5712-5713
order: 5712
cycles: false
bibtex_author: Whitehouse, Justin and Jung, Christopher and Syrgkanis, Vasilis and
  Wilder, Bryan and Wu, Zhiwei Steven
author:
- given: Justin
  family: Whitehouse
- given: Christopher
  family: Jung
- given: Vasilis
  family: Syrgkanis
- given: Bryan
  family: Wilder
- given: Zhiwei Steven
  family: Wu
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
pdf: https://raw.githubusercontent.com/mlresearch/v291/main/assets/whitehouse25a/whitehouse25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
