---
title: Faster Algorithms for Learning Convex Functions
booktitle: Proceedings of the 39th International Conference on Machine Learning
abstract: The task of approximating an arbitrary convex function arises in several
  learning problems such as convex regression, learning with a difference of convex
  (DC) functions, and learning Bregman or $f$-divergences. In this paper, we develop
  and analyze an approach for solving a broad range of convex function learning problems
  that is faster than state-of-the-art approaches. Our approach is based on a 2-block
  ADMM method where each block can be computed in closed form. For the task of convex
  Lipschitz regression, we establish that our proposed algorithm converges with iteration
  complexity of $ O(n\sqrt{d}/\epsilon)$ for a dataset $\bm X \in \mathbb R^{n\times
  d}$ and $\epsilon > 0$. Combined with per-iteration computation complexity, our
  method converges with the rate $O(n^3 d^{1.5}/\epsilon+n^2 d^{2.5}/\epsilon+n d^3/\epsilon)$.
  This new rate improves the state of the art rate of $O(n^5d^2/\epsilon)$ if $d =
  o( n^4)$. Further we provide similar solvers for DC regression and Bregman divergence
  learning. Unlike previous approaches, our method is amenable to the use of GPUs.
  We demonstrate on regression and metric learning experiments that our approach is
  over 100 times faster than existing approaches on some data sets, and produces results
  that are comparable to state of the art.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: siahkamari22a
month: 0
tex_title: Faster Algorithms for Learning Convex Functions
firstpage: 20176
lastpage: 20194
page: 20176-20194
order: 20176
cycles: false
bibtex_author: Siahkamari, Ali and Acar, Durmus Alp Emre and Liao, Christopher and
  Geyer, Kelly L and Saligrama, Venkatesh and Kulis, Brian
author:
- given: Ali
  family: Siahkamari
- given: Durmus Alp Emre
  family: Acar
- given: Christopher
  family: Liao
- given: Kelly L
  family: Geyer
- given: Venkatesh
  family: Saligrama
- given: Brian
  family: Kulis
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
pdf: https://proceedings.mlr.press/v162/siahkamari22a/siahkamari22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
