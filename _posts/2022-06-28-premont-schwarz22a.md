---
title: A Simple Guard for Learned Optimizers
booktitle: Proceedings of the 39th International Conference on Machine Learning
abstract: If the trend of learned components eventually outperforming their hand-crafted
  version continues, learned optimizers will eventually outperform hand-crafted optimizers
  like SGD or Adam. Even if learned optimizers (L2Os) eventually outpace hand-crafted
  ones in practice however, they are still not provably convergent and might fail
  out of distribution. These are the questions addressed here. Currently, learned
  optimizers frequently outperform generic hand-crafted optimizers (such as gradient
  descent) at the beginning of learning but they generally plateau after some time
  while the generic algorithms continue to make progress and often overtake the learned
  algorithm as Aesop’s tortoise which overtakes the hare. L2Os also still have a difficult
  time generalizing out of distribution. \cite{heaton_safeguarded_2020} proposed Safeguarded
  L2O (GL2O) which can take a learned optimizer and safeguard it with a generic learning
  algorithm so that by conditionally switching between the two, the resulting algorithm
  is provably convergent. We propose a new class of Safeguarded L2O, called Loss-Guarded
  L2O (LGL2O), which is both conceptually simpler and computationally less expensive.
  The guarding mechanism decides solely based on the expected future loss value of
  both optimizers. Furthermore, we show theoretical proof of LGL2O’s convergence guarantee
  and empirical results comparing to GL2O and other baselines showing that it combines
  the best of both L2O and SGD and that in practice converges much better than GL2O.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: premont-schwarz22a
month: 0
tex_title: A Simple Guard for Learned Optimizers
firstpage: 17910
lastpage: 17925
page: 17910-17925
order: 17910
cycles: false
bibtex_author: Pr{\'e}mont-Schwarz, Isabeau and V\'{\i}tk{\r{u}}, Jaroslav and Feyereisl,
  Jan
author:
- given: Isabeau
  family: Prémont-Schwarz
- given: Jaroslav
  family: Vı́tků
- given: Jan
  family: Feyereisl
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
pdf: https://proceedings.mlr.press/v162/premont-schwarz22a/premont-schwarz22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
