---
title: 'RieszNet and ForestRiesz: Automatic Debiased Machine Learning with Neural
  Nets and Random Forests'
booktitle: Proceedings of the 39th International Conference on Machine Learning
abstract: Many causal and policy effects of interest are defined by linear functionals
  of high-dimensional or non-parametric regression functions. $\sqrt{n}$-consistent
  and asymptotically normal estimation of the object of interest requires debiasing
  to reduce the effects of regularization and/or model selection on the object of
  interest. Debiasing is typically achieved by adding a correction term to the plug-in
  estimator of the functional, which leads to properties such as semi-parametric efficiency,
  double robustness, and Neyman orthogonality. We implement an automatic debiasing
  procedure based on automatically learning the Riesz representation of the linear
  functional using Neural Nets and Random Forests. Our method only relies on black-box
  evaluation oracle access to the linear functional and does not require knowledge
  of its analytic form. We propose a multitasking Neural Net debiasing method with
  stochastic gradient descent minimization of a combined Riesz representer and regression
  loss, while sharing representation layers for the two functions. We also propose
  a Random Forest method which learns a locally linear representation of the Riesz
  function. Even though our method applies to arbitrary functionals, we experimentally
  find that it performs well compared to the state of art neural net based algorithm
  of Shi et al. (2019) for the case of the average treatment effect functional. We
  also evaluate our method on the problem of estimating average marginal effects with
  continuous treatments, using semi-synthetic data of gasoline price changes on gasoline
  demand.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chernozhukov22a
month: 0
tex_title: "{R}iesz{N}et and {F}orest{R}iesz: Automatic Debiased Machine Learning
  with Neural Nets and Random Forests"
firstpage: 3901
lastpage: 3914
page: 3901-3914
order: 3901
cycles: false
bibtex_author: Chernozhukov, Victor and Newey, Whitney and Quintas-Mart\'{\i}nez,
  V\'{\i}ctor M and Syrgkanis, Vasilis
author:
- given: Victor
  family: Chernozhukov
- given: Whitney
  family: Newey
- given: Vı́ctor M
  family: Quintas-Martı́nez
- given: Vasilis
  family: Syrgkanis
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
pdf: https://proceedings.mlr.press/v162/chernozhukov22a/chernozhukov22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
