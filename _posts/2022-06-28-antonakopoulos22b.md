---
title: 'UnderGrad: A Universal Black-Box Optimization Method with Almost Dimension-Free
  Convergence Rate Guarantees'
booktitle: Proceedings of the 39th International Conference on Machine Learning
abstract: Universal methods achieve optimal convergence rate guarantees in convex
  optimization without any prior knowledge of the problem’s regularity parameters
  or the attributes of the gradient oracle employed by the method. In this regard,
  existing state-of-the-art algorithms achieve an $O(1/T^2)$ convergence rate in Lipschitz
  smooth problems with a perfect gradient oracle, and an $O(1/sqrt{T})$ convergence
  speed when the underlying problem is non-smooth and/or the gradient oracle is stochastic.
  On the downside, these methods do not take into account the dependence of these
  guarantees on the problem’s dimensionality, and this can have a catastrophic impact
  on a method’s convergence, in both theory and practice. Our paper aims to bridge
  this gap by providing a scalable universal method - dubbed UnDERGrad - which enjoys
  an almost dimension-free oracle complexity in problems with a favorable geometry
  (like the simplex, $\ell_1$-ball or trace-constraints), while retaining the order-optimal
  dependence on T described above. These "best of both worlds" guarantees are achieved
  via a primal-dual update scheme inspired by the dual exploration method for variational
  inequalities.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: antonakopoulos22b
month: 0
tex_title: "{U}nder{G}rad: A Universal Black-Box Optimization Method with Almost Dimension-Free
  Convergence Rate Guarantees"
firstpage: 772
lastpage: 795
page: 772-795
order: 772
cycles: false
bibtex_author: Antonakopoulos, Kimon and Vu, Dong Quan and Cevher, Volkan and Levy,
  Kfir and Mertikopoulos, Panayotis
author:
- given: Kimon
  family: Antonakopoulos
- given: Dong Quan
  family: Vu
- given: Volkan
  family: Cevher
- given: Kfir
  family: Levy
- given: Panayotis
  family: Mertikopoulos
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
pdf: https://proceedings.mlr.press/v162/antonakopoulos22b/antonakopoulos22b.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
