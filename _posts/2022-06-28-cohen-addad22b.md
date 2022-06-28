---
title: Massively Parallel $k$-Means Clustering for Perturbation Resilient Instances
booktitle: Proceedings of the 39th International Conference on Machine Learning
abstract: We consider $k$-means clustering of $n$ data points in Euclidean space in
  the Massively Parallel Computation (MPC) model, a computational model which is an
  abstraction of modern massively parallel computing system such as MapReduce. Recent
  work provides evidence that getting $O(1)$-approximate $k$-means solution for general
  input points using $o(\log n)$ rounds in the MPC model may be impossible under certain
  conditions [Ghaffari, Kuhn \& Uitto’2019]. However, the real-world data points usually
  have better structures. One instance of interest is the set of data points which
  is perturbation resilient [Bilu \& Linial’2010]. In particular, a point set is $\alpha$-perturbation
  resilient for $k$-means if perturbing pairwise distances by multiplicative factors
  in the range $[1,\alpha]$ does not change the optimum $k$-means clusters. We bypass
  the worst case lower bound by considering the perturbation resilient input points
  and showing $o(\log n)$ rounds $k$-means clustering algorithms for these instances
  in the MPC model. Specifically, we show a fully scalable $(1+\varepsilon)$-approximate
  $k$-means clustering algorithm for $O(\alpha)$-perturbation resilient instance in
  the MPC model using $O(1)$ rounds and ${O}_{\varepsilon,d}(n^{1+1/\alpha^2+o(1)})$
  total space. If the space per machine is sufficiently larger than $k$, i.e., at
  least $k\cdot n^{\Omega(1)}$, we also develop an optimal $k$-means clustering algorithm
  for $O(\alpha)$-perturbation resilient instance in MPC using $O(1)$ rounds and ${O}_d(n^{1+o(1)}\cdot(n^{1/\alpha^2}+k))$
  total space.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: cohen-addad22b
month: 0
tex_title: Massively Parallel $k$-Means Clustering for Perturbation Resilient Instances
firstpage: 4180
lastpage: 4201
page: 4180-4201
order: 4180
cycles: false
bibtex_author: Cohen-Addad, Vincent and Mirrokni, Vahab and Zhong, Peilin
author:
- given: Vincent
  family: Cohen-Addad
- given: Vahab
  family: Mirrokni
- given: Peilin
  family: Zhong
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
pdf: https://proceedings.mlr.press/v162/cohen-addad22b/cohen-addad22b.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
