---
title: Scaling Gaussian Process Optimization by Evaluating a Few Unique Candidates
  Multiple Times
booktitle: Proceedings of the 39th International Conference on Machine Learning
abstract: Computing a Gaussian process (GP) posterior has a computational cost cubical
  in the number of historical points. A reformulation of the same GP posterior highlights
  that this complexity mainly depends on how many <em>unique</em> historical points
  are considered. This can have important implication in active learning settings,
  where the set of historical points is constructed sequentially by the learner. We
  show that sequential black-box optimization based on GPs (GP-Opt) can be made efficient
  by sticking to a candidate solution for multiple evaluation steps and switch only
  when necessary. Limiting the number of switches also limits the number of unique
  points in the history of the GP. Thus, the efficient GP reformulation can be used
  to exactly and cheaply compute the posteriors required to run the GP-Opt algorithms.
  This approach is especially useful in real-world applications of GP-Opt with high
  switch costs (e.g. switching chemicals in wet labs, data/model loading in hyperparameter
  optimization). As examples of this meta-approach, we modify two well-established
  GP-Opt algorithms, GP-UCB and GP-EI, to switch candidates as infrequently as possible
  adapting rules from batched GP-Opt. These versions preserve all the theoretical
  no-regret guarantees while improving practical aspects of the algorithms such as
  runtime, memory complexity, and the ability of batching candidates and evaluating
  them in parallel.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: calandriello22a
month: 0
tex_title: Scaling {G}aussian Process Optimization by Evaluating a Few Unique Candidates
  Multiple Times
firstpage: 2523
lastpage: 2541
page: 2523-2541
order: 2523
cycles: false
bibtex_author: Calandriello, Daniele and Carratino, Luigi and Lazaric, Alessandro
  and Valko, Michal and Rosasco, Lorenzo
author:
- given: Daniele
  family: Calandriello
- given: Luigi
  family: Carratino
- given: Alessandro
  family: Lazaric
- given: Michal
  family: Valko
- given: Lorenzo
  family: Rosasco
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
pdf: https://proceedings.mlr.press/v162/calandriello22a/calandriello22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
