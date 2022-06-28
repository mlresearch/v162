---
title: AdaGrad Avoids Saddle Points
booktitle: Proceedings of the 39th International Conference on Machine Learning
abstract: Adaptive first-order methods in optimization have widespread ML applications
  due to their ability to adapt to non-convex landscapes. However, their convergence
  guarantees are typically stated in terms of vanishing gradient norms, which leaves
  open the issue of converging to undesirable saddle points (or even local maxima).
  In this paper, we focus on the AdaGrad family of algorithms - from scalar to full-matrix
  preconditioning - and we examine the question of whether the method’s trajectories
  avoid saddle points. A major challenge that arises here is that AdaGrad’s step-size
  (or, more accurately, the method’s preconditioner) evolves over time in a filtration-dependent
  way, i.e., as a function of all gradients observed in earlier iterations; as a result,
  avoidance results for methods with a constant or vanishing step-size do not apply.
  We resolve this challenge by combining a series of step-size stabilization arguments
  with a recursive representation of the AdaGrad preconditioner that allows us to
  employ center-stable techniques and ultimately show that the induced trajectories
  avoid saddle points from almost any initial condition.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: antonakopoulos22a
month: 0
tex_title: "{A}da{G}rad Avoids Saddle Points"
firstpage: 731
lastpage: 771
page: 731-771
order: 731
cycles: false
bibtex_author: Antonakopoulos, Kimon and Mertikopoulos, Panayotis and Piliouras, Georgios
  and Wang, Xiao
author:
- given: Kimon
  family: Antonakopoulos
- given: Panayotis
  family: Mertikopoulos
- given: Georgios
  family: Piliouras
- given: Xiao
  family: Wang
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
pdf: https://proceedings.mlr.press/v162/antonakopoulos22a/antonakopoulos22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
