---
title: Constrained Discrete Black-Box Optimization using Mixed-Integer Programming
booktitle: Proceedings of the 39th International Conference on Machine Learning
abstract: Discrete black-box optimization problems are challenging for model-based
  optimization (MBO) algorithms, such as Bayesian optimization, due to the size of
  the search space and the need to satisfy combinatorial constraints. In particular,
  these methods require repeatedly solving a complex discrete global optimization
  problem in the inner loop, where popular heuristic inner-loop solvers introduce
  approximations and are difficult to adapt to combinatorial constraints. In response,
  we propose NN+MILP, a general discrete MBO framework using piecewise-linear neural
  networks as surrogate models and mixed-integer linear programming (MILP) to optimize
  the acquisition function. MILP provides optimality guarantees and a versatile declarative
  language for domain-specific constraints. We test our approach on a range of unconstrained
  and constrained problems, including DNA binding, constrained binary quadratic problems
  from the MINLPLib benchmark, and the NAS-Bench-101 neural architecture search benchmark.
  NN+MILP surpasses or matches the performance of black-box algorithms tailored to
  the constraints at hand, with global optimization of the acquisition problem running
  in a few minutes using only standard software packages and hardware.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: papalexopoulos22a
month: 0
tex_title: Constrained Discrete Black-Box Optimization using Mixed-Integer Programming
firstpage: 17295
lastpage: 17322
page: 17295-17322
order: 17295
cycles: false
bibtex_author: Papalexopoulos, Theodore P and Tjandraatmadja, Christian and Anderson,
  Ross and Vielma, Juan Pablo and Belanger, David
author:
- given: Theodore P
  family: Papalexopoulos
- given: Christian
  family: Tjandraatmadja
- given: Ross
  family: Anderson
- given: Juan Pablo
  family: Vielma
- given: David
  family: Belanger
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
pdf: https://proceedings.mlr.press/v162/papalexopoulos22a/papalexopoulos22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
