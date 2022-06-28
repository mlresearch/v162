---
title: Differentially Private Maximal Information Coefficients
booktitle: Proceedings of the 39th International Conference on Machine Learning
abstract: The Maximal Information Coefficient (MIC) is a powerful statistic to identify
  dependencies between variables. However, it may be applied to sensitive data, and
  publishing it could leak private information. As a solution, we present algorithms
  to approximate MIC in a way that provides differential privacy. We show that the
  natural application of the classic Laplace mechanism yields insufficient accuracy.
  We therefore introduce the MICr statistic, which is a new MIC approximation that
  is more compatible with differential privacy. We prove MICr is a consistent estimator
  for MIC, and we provide two differentially private versions of it. We perform experiments
  on a variety of real and synthetic datasets. The results show that the private MICr
  statistics significantly outperform direct application of the Laplace mechanism.
  Moreover, experiments on real-world datasets show accuracy that is usable when the
  sample size is at least moderately large.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: lazarsfeld22a
month: 0
tex_title: Differentially Private Maximal Information Coefficients
firstpage: 12126
lastpage: 12163
page: 12126-12163
order: 12126
cycles: false
bibtex_author: Lazarsfeld, John and Johnson, Aaron and Adeniran, Emmanuel
author:
- given: John
  family: Lazarsfeld
- given: Aaron
  family: Johnson
- given: Emmanuel
  family: Adeniran
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
pdf: https://proceedings.mlr.press/v162/lazarsfeld22a/lazarsfeld22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
