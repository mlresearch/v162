---
title: Scalable Computation of Causal Bounds
booktitle: Proceedings of the 39th International Conference on Machine Learning
abstract: We consider the problem of computing bounds for causal inference problems
  with unobserved confounders, where identifiability does not hold. Existing non-parametric
  approaches for computing such bounds use linear programming (LP) formulations that
  quickly become intractable for existing solvers because the size of the LP grows
  exponentially in the number of edges in the underlying causal graph. We show that
  this LP can be significantly pruned by carefully considering the structure of the
  causal query, allowing us to compute bounds for significantly larger causal inference
  problems as compared to what is possible using existing techniques. This pruning
  procedure also allows us to compute the bounds in closed form for a special class
  of causal graphs and queries, which includes a well-studied family of problems where
  multiple confounded treatments influence an outcome. We also propose a very efficient
  greedy heuristic that produces very high quality bounds, and scales to problems
  that are several orders of magnitude larger than those for which the pruned LP can
  be solved.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: shridharan22a
month: 0
tex_title: Scalable Computation of Causal Bounds
firstpage: 20125
lastpage: 20140
page: 20125-20140
order: 20125
cycles: false
bibtex_author: Shridharan, Madhumitha and Iyengar, Garud
author:
- given: Madhumitha
  family: Shridharan
- given: Garud
  family: Iyengar
date: 2022-06-28
address:
container-title: Proceedings of the 39th International Conference on Machine Learning
volume: '162'
genre: inproceedings
issued:
  date-parts:
  - 2022
  - 6
  - 28
pdf: https://proceedings.mlr.press/v162/shridharan22a/shridharan22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
