---
title: Nonparametric Sparse Tensor Factorization with Hierarchical Gamma Processes
booktitle: Proceedings of the 39th International Conference on Machine Learning
abstract: We propose a nonparametric factorization approach for sparsely observed
  tensors. The sparsity does not mean zero-valued entries are massive or dominated.
  Rather, it implies the observed entries are very few, and even fewer with the growth
  of the tensor; this is ubiquitous in practice. Compared with the existent works,
  our model not only leverages the structural information underlying the observed
  entry indices, but also provides extra interpretability and flexibility {—} it can
  simultaneously estimate a set of location factors about the intrinsic properties
  of the tensor nodes, and another set of sociability factors reflecting their extrovert
  activity in interacting with others; users are free to choose a trade-off between
  the two types of factors. Specifically, we use hierarchical Gamma processes and
  Poisson random measures to construct a tensor-valued process, which can freely sample
  the two types of factors to generate tensors and always guarantees an asymptotic
  sparsity. We then normalize the tensor process to obtain hierarchical Dirichlet
  processes to sample each observed entry index, and use a Gaussian process to sample
  the entry value as a nonlinear function of the factors, so as to capture both the
  sparse structure properties and complex node relationships. For efficient inference,
  we use Dirichlet process properties over finite sample partitions, density transformations,
  and random features to develop a stochastic variational estimation algorithm. We
  demonstrate the advantage of our method in several benchmark datasets.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: tillinghast22a
month: 0
tex_title: Nonparametric Sparse Tensor Factorization with Hierarchical Gamma Processes
firstpage: 21432
lastpage: 21448
page: 21432-21448
order: 21432
cycles: false
bibtex_author: Tillinghast, Conor and Wang, Zheng and Zhe, Shandian
author:
- given: Conor
  family: Tillinghast
- given: Zheng
  family: Wang
- given: Shandian
  family: Zhe
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
pdf: https://proceedings.mlr.press/v162/tillinghast22a/tillinghast22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
