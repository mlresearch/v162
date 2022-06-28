---
title: Adaptive Second Order Coresets for Data-efficient Machine Learning
booktitle: Proceedings of the 39th International Conference on Machine Learning
abstract: Training machine learning models on massive datasets incurs substantial
  computational costs. To alleviate such costs, there has been a sustained effort
  to develop data-efficient training methods that can carefully select subsets of
  the training examples that generalize on par with the full training data. However,
  existing methods are limited in providing theoretical guarantees for the quality
  of the models trained on the extracted subsets, and may perform poorly in practice.
  We propose AdaCore, a method that leverages the geometry of the data to extract
  subsets of the training examples for efficient machine learning. The key idea behind
  our method is to dynamically approximate the curvature of the loss function via
  an exponentially-averaged estimate of the Hessian to select weighted subsets (coresets)
  that provide a close approximation of the full gradient preconditioned with the
  Hessian. We prove rigorous guarantees for the convergence of various first and second-order
  methods applied to the subsets chosen by AdaCore. Our extensive experiments show
  that AdaCore extracts coresets with higher quality compared to baselines and speeds
  up training of convex and non-convex machine learning models, such as logistic regression
  and neural networks, by over 2.9x over the full data and 4.5x over random subsets.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: pooladzandi22a
month: 0
tex_title: Adaptive Second Order Coresets for Data-efficient Machine Learning
firstpage: 17848
lastpage: 17869
page: 17848-17869
order: 17848
cycles: false
bibtex_author: Pooladzandi, Omead and Davini, David and Mirzasoleiman, Baharan
author:
- given: Omead
  family: Pooladzandi
- given: David
  family: Davini
- given: Baharan
  family: Mirzasoleiman
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
pdf: https://proceedings.mlr.press/v162/pooladzandi22a/pooladzandi22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
