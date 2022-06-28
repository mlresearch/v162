---
title: Towards Understanding Sharpness-Aware Minimization
booktitle: Proceedings of the 39th International Conference on Machine Learning
abstract: Sharpness-Aware Minimization (SAM) is a recent training method that relies
  on worst-case weight perturbations which significantly improves generalization in
  various settings. We argue that the existing justifications for the success of SAM
  which are based on a PAC-Bayes generalization bound and the idea of convergence
  to flat minima are incomplete. Moreover, there are no explanations for the success
  of using m-sharpness in SAM which has been shown as essential for generalization.
  To better understand this aspect of SAM, we theoretically analyze its implicit bias
  for diagonal linear networks. We prove that SAM always chooses a solution that enjoys
  better generalization properties than standard gradient descent for a certain class
  of problems, and this effect is amplified by using m-sharpness. We further study
  the properties of the implicit bias on non-linear networks empirically, where we
  show that fine-tuning a standard model with SAM can lead to significant generalization
  improvements. Finally, we provide convergence results of SAM for non-convex objectives
  when used with stochastic gradients. We illustrate these results empirically for
  deep networks and discuss their relation to the generalization behavior of SAM.
  The code of our experiments is available at https://github.com/tml-epfl/understanding-sam.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: andriushchenko22a
month: 0
tex_title: Towards Understanding Sharpness-Aware Minimization
firstpage: 639
lastpage: 668
page: 639-668
order: 639
cycles: false
bibtex_author: Andriushchenko, Maksym and Flammarion, Nicolas
author:
- given: Maksym
  family: Andriushchenko
- given: Nicolas
  family: Flammarion
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
pdf: https://proceedings.mlr.press/v162/andriushchenko22a/andriushchenko22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
