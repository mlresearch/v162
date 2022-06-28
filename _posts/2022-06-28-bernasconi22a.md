---
title: 'Safe Learning in Tree-Form Sequential Decision Making: Handling Hard and Soft
  Constraints'
booktitle: Proceedings of the 39th International Conference on Machine Learning
abstract: We study decision making problems in which an agent sequentially interacts
  with a stochastic environment defined by means of a tree structure. The agent repeatedly
  faces the environment over time, and, after each round, it perceives a utility and
  a cost, which are both stochastic. The goal of the agent is to learn an optimal
  strategy in an online fashion, while, at the same time, keeping costs below a given
  safety threshold. Our model naturally fits many real-world scenarios, such as, e.g.,
  opponent exploitation in games and web link selection. We study the hard-threshold
  problem of achieving sublinear regret while guaranteeing that the threshold constraint
  is satisfied at every iteration with high probability. First, we show that, in general,
  any algorithm with such a guarantee incurs in a linear regret. This motivates the
  introduction of a relaxed problem, namely the soft-threshold problem, in which we
  only require that the cumulative violation of the threshold constraint grows sublinearly,
  and, thus, we can provide an algorithm with sublinear regret. Next, we show how,
  in the hard-threshold problem, a sublinear regret algorithm can be designed under
  the additional assumption that there exists a known strategy strictly satisfying
  the threshold constraint. We also show that our regret bounds are tight. Finally,
  we cast the opponent exploitation problem to our model, and we experimentally evaluate
  our algorithms on a standard testbed of games.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bernasconi22a
month: 0
tex_title: 'Safe Learning in Tree-Form Sequential Decision Making: Handling Hard and
  Soft Constraints'
firstpage: 1854
lastpage: 1873
page: 1854-1873
order: 1854
cycles: false
bibtex_author: Bernasconi, Martino and Cacciamani, Federico and Castiglioni, Matteo
  and Marchesi, Alberto and Gatti, Nicola and Trov{\`o}, Francesco
author:
- given: Martino
  family: Bernasconi
- given: Federico
  family: Cacciamani
- given: Matteo
  family: Castiglioni
- given: Alberto
  family: Marchesi
- given: Nicola
  family: Gatti
- given: Francesco
  family: Trovò
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
pdf: https://proceedings.mlr.press/v162/bernasconi22a/bernasconi22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
