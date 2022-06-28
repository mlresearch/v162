---
title: Prioritized Training on Points that are Learnable, Worth Learning, and not
  yet Learnt
booktitle: Proceedings of the 39th International Conference on Machine Learning
abstract: 'Training on web-scale data can take months. But much computation and time
  is wasted on redundant and noisy points that are already learnt or not learnable.
  To accelerate training, we introduce Reducible Holdout Loss Selection (RHO-LOSS),
  a simple but principled technique which selects approximately those points for training
  that most reduce the model’s generalization loss. As a result, RHO-LOSS mitigates
  the weaknesses of existing data selection methods: techniques from the optimization
  literature typically select "hard" (e.g. high loss) points, but such points are
  often noisy (not learnable) or less task-relevant. Conversely, curriculum learning
  prioritizes "easy" points, but such points need not be trained on once learned.
  In contrast, RHO-LOSS selects points that are learnable, worth learning, and not
  yet learnt. RHO-LOSS trains in far fewer steps than prior art, improves accuracy,
  and speeds up training on a wide range of datasets, hyperparameters, and architectures
  (MLPs, CNNs, and BERT). On the large web-scraped image dataset Clothing-1M, RHO-LOSS
  trains in 18x fewer steps and reaches 2% higher final accuracy than uniform data
  shuffling.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: mindermann22a
month: 0
tex_title: Prioritized Training on Points that are Learnable, Worth Learning, and
  not yet Learnt
firstpage: 15630
lastpage: 15649
page: 15630-15649
order: 15630
cycles: false
bibtex_author: Mindermann, S{\"o}ren and Brauner, Jan M and Razzak, Muhammed T and
  Sharma, Mrinank and Kirsch, Andreas and Xu, Winnie and H{\"o}ltgen, Benedikt and
  Gomez, Aidan N and Morisot, Adrien and Farquhar, Sebastian and Gal, Yarin
author:
- given: Sören
  family: Mindermann
- given: Jan M
  family: Brauner
- given: Muhammed T
  family: Razzak
- given: Mrinank
  family: Sharma
- given: Andreas
  family: Kirsch
- given: Winnie
  family: Xu
- given: Benedikt
  family: Höltgen
- given: Aidan N
  family: Gomez
- given: Adrien
  family: Morisot
- given: Sebastian
  family: Farquhar
- given: Yarin
  family: Gal
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
pdf: https://proceedings.mlr.press/v162/mindermann22a/mindermann22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
