---
title: 'Generic Coreset for Scalable Learning of Monotonic Kernels: Logistic Regression,
  Sigmoid and more'
booktitle: Proceedings of the 39th International Conference on Machine Learning
abstract: 'Coreset (or core-set) is a small weighted <em>subset</em> $Q$ of an input
  set $P$ with respect to a given <em>monotonic</em> function $f:\mathbb{R}\to\mathbb{R}$
  that <em>provably</em> approximates its fitting loss $\sum_{p\in P}f(p\cdot x)$
  to <em>any</em> given $x\in\mathbb{R}^d$. Using $Q$ we can obtain an approximation
  of $x^*$ that minimizes this loss, by running <em>existing</em> optimization algorithms
  on $Q$. In this work we provide: (i) A lower bound which proves that there are sets
  with no coresets smaller than $n=|P|$ for general monotonic loss functions. (ii)
  A proof that, with an additional common regularization term and under a natural
  assumption that holds e.g. for logistic regression and the sigmoid activation functions,
  a small coreset exists for <em>any</em> input $P$. (iii) A generic coreset construction
  algorithm that computes such a small coreset $Q$ in $O(nd+n\log n)$ time, and (iv)
  Experimental results with open-source code which demonstrate that our coresets are
  effective and are much smaller in practice than predicted in theory.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: tolochinksy22a
month: 0
tex_title: 'Generic Coreset for Scalable Learning of Monotonic Kernels: Logistic Regression,
  Sigmoid and more'
firstpage: 21520
lastpage: 21547
page: 21520-21547
order: 21520
cycles: false
bibtex_author: Tolochinksy, Elad and Jubran, Ibrahim and Feldman, Dan
author:
- given: Elad
  family: Tolochinksy
- given: Ibrahim
  family: Jubran
- given: Dan
  family: Feldman
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
pdf: https://proceedings.mlr.press/v162/tolochinksy22a/tolochinksy22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
