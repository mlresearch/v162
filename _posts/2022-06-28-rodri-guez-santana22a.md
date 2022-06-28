---
title: Function-space Inference with Sparse Implicit Processes
booktitle: Proceedings of the 39th International Conference on Machine Learning
abstract: Implicit Processes (IPs) represent a flexible framework that can be used
  to describe a wide variety of models, from Bayesian neural networks, neural samplers
  and data generators to many others. IPs also allow for approximate inference in
  function-space. This change of formulation solves intrinsic degenerate problems
  of parameter-space approximate inference concerning the high number of parameters
  and their strong dependencies in large models. For this, previous works in the literature
  have attempted to employ IPs both to set up the prior and to approximate the resulting
  posterior. However, this has proven to be a challenging task. Existing methods that
  can tune the prior IP result in a Gaussian predictive distribution, which fails
  to capture important data patterns. By contrast, methods producing flexible predictive
  distributions by using another IP to approximate the posterior process cannot tune
  the prior IP to the observed data. We propose here the first method that can accomplish
  both goals. For this, we rely on an inducing-point representation of the prior IP,
  as often done in the context of sparse Gaussian processes. The result is a scalable
  method for approximate inference with IPs that can tune the prior IP parameters
  to the data, and that provides accurate non-Gaussian predictive distributions.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: rodri-guez-santana22a
month: 0
tex_title: Function-space Inference with Sparse Implicit Processes
firstpage: 18723
lastpage: 18740
page: 18723-18740
order: 18723
cycles: false
bibtex_author: Rodr\'{\i}guez-Santana, Simon and Zaldivar, Bryan and Hernandez-Lobato,
  Daniel
author:
- given: Simon
  family: Rodrı́guez-Santana
- given: Bryan
  family: Zaldivar
- given: Daniel
  family: Hernandez-Lobato
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
pdf: https://proceedings.mlr.press/v162/rodri-guez-santana22a/rodri-guez-santana22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
