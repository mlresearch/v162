---
title: 'ProxSkip: Yes! Local Gradient Steps Provably Lead to Communication Acceleration!
  Finally!'
booktitle: Proceedings of the 39th International Conference on Machine Learning
abstract: 'We introduce ProxSkip—a surprisingly simple and provably efficient method
  for minimizing the sum of a smooth ($f$) and an expensive nonsmooth proximable ($\psi$)
  function. The canonical approach to solving such problems is via the proximal gradient
  descent (ProxGD) algorithm, which is based on the evaluation of the gradient of
  $f$ and the prox operator of $\psi$ in each iteration. In this work we are specifically
  interested in the regime in which the evaluation of prox is costly relative to the
  evaluation of the gradient, which is the case in many applications. ProxSkip allows
  for the expensive prox operator to be skipped in most iterations: while its iteration
  complexity is $\mathcal{O}(\kappa \log \nicefrac{1}{\varepsilon})$, where $\kappa$
  is the condition number of $f$, the number of prox evaluations is $\mathcal{O}(\sqrt{\kappa}
  \log \nicefrac{1}{\varepsilon})$ only. Our main motivation comes from federated
  learning, where evaluation of the gradient operator corresponds to taking a local
  GD step independently on all devices, and evaluation of prox corresponds to (expensive)
  communication in the form of gradient averaging. In this context, ProxSkip offers
  an effective <em>acceleration</em> of communication complexity. Unlike other local
  gradient-type methods, such as FedAvg, SCAFFOLD, S-Local-GD and FedLin, whose theoretical
  communication complexity is worse than, or at best matching, that of vanilla GD
  in the heterogeneous data regime, we obtain a provable and large improvement without
  any heterogeneity-bounding assumptions.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: mishchenko22b
month: 0
tex_title: "{P}rox{S}kip: Yes! {L}ocal Gradient Steps Provably Lead to Communication
  Acceleration! {F}inally!"
firstpage: 15750
lastpage: 15769
page: 15750-15769
order: 15750
cycles: false
bibtex_author: Mishchenko, Konstantin and Malinovsky, Grigory and Stich, Sebastian
  and Richtarik, Peter
author:
- given: Konstantin
  family: Mishchenko
- given: Grigory
  family: Malinovsky
- given: Sebastian
  family: Stich
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
pdf: https://proceedings.mlr.press/v162/mishchenko22b/mishchenko22b.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
