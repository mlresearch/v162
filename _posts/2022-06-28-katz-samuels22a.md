---
title: Training OOD Detectors in their Natural Habitats
booktitle: Proceedings of the 39th International Conference on Machine Learning
abstract: Out-of-distribution (OOD) detection is important for machine learning models
  deployed in the wild. Recent methods use auxiliary outlier data to regularize the
  model for improved OOD detection. However, these approaches make a strong distributional
  assumption that the auxiliary outlier data is completely separable from the in-distribution
  (ID) data. In this paper, we propose a novel framework that leverages wild mixture
  data—that naturally consists of both ID and OOD samples. Such wild data is abundant
  and arises freely upon deploying a machine learning classifier in their natural
  habitats. Our key idea is to formulate a constrained optimization problem and to
  show how to tractably solve it. Our learning objective maximizes the OOD detection
  rate, subject to constraints on the classification error of ID data and on the OOD
  error rate of ID examples. We extensively evaluate our approach on common OOD detection
  tasks and demonstrate superior performance. Code is available at https://github.com/jkatzsam/woods_ood.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: katz-samuels22a
month: 0
tex_title: Training {OOD} Detectors in their Natural Habitats
firstpage: 10848
lastpage: 10865
page: 10848-10865
order: 10848
cycles: false
bibtex_author: Katz-Samuels, Julian and Nakhleh, Julia B and Nowak, Robert and Li,
  Yixuan
author:
- given: Julian
  family: Katz-Samuels
- given: Julia B
  family: Nakhleh
- given: Robert
  family: Nowak
- given: Yixuan
  family: Li
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
pdf: https://proceedings.mlr.press/v162/katz-samuels22a/katz-samuels22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
