---
title: Proximal and Federated Random Reshuffling
booktitle: Proceedings of the 39th International Conference on Machine Learning
abstract: 'Random Reshuffling (RR), also known as Stochastic Gradient Descent (SGD)
  without replacement, is a popular and theoretically grounded method for finite-sum
  minimization. We propose two new algorithms: Proximal and Federated Random Reshuffling
  (ProxRR and FedRR). The first algorithm, ProxRR, solves composite finite-sum minimization
  problems in which the objective is the sum of a (potentially non-smooth) convex
  regularizer and an average of $n$ smooth objectives. ProxRR evaluates the proximal
  operator once per epoch only. When the proximal operator is expensive to compute,
  this small difference makes ProxRR up to $n$ times faster than algorithms that evaluate
  the proximal operator in every iteration, such as proximal (stochastic) gradient
  descent. We give examples of practical optimization tasks where the proximal operator
  is difficult to compute and ProxRR has a clear advantage. One such task is federated
  or distributed optimization, where the evaluation of the proximal operator corresponds
  to communication across the network. We obtain our second algorithm, FedRR, as a
  special case of ProxRR applied to federated optimization, and prove it has a smaller
  communication footprint than either distributed gradient descent or Local SGD. Our
  theory covers both constant and decreasing stepsizes, and allows for importance
  resampling schemes that can improve conditioning, which may be of independent interest.
  Our theory covers both convex and nonconvex regimes. Finally, we corroborate our
  results with experiments on real data sets.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: mishchenko22a
month: 0
tex_title: Proximal and Federated Random Reshuffling
firstpage: 15718
lastpage: 15749
page: 15718-15749
order: 15718
cycles: false
bibtex_author: Mishchenko, Konstantin and Khaled, Ahmed and Richtarik, Peter
author:
- given: Konstantin
  family: Mishchenko
- given: Ahmed
  family: Khaled
- given: Peter
  family: Richtarik
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
pdf: https://proceedings.mlr.press/v162/mishchenko22a/mishchenko22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
