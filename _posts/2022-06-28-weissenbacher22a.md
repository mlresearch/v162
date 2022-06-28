---
title: 'Koopman Q-learning: Offline Reinforcement Learning via Symmetries of Dynamics'
booktitle: Proceedings of the 39th International Conference on Machine Learning
abstract: Offline reinforcement learning leverages large datasets to train policies
  without interactions with the environment. The learned policies may then be deployed
  in real-world settings where interactions are costly or dangerous. Current algorithms
  over-fit to the training dataset and as a consequence perform poorly when deployed
  to out-of-distribution generalizations of the environment. We aim to address these
  limitations by learning a Koopman latent representation which allows us to infer
  symmetries of the system’s underlying dynamic. The latter is then utilized to extend
  the otherwise static offline dataset during training; this constitutes a novel data
  augmentation framework which reflects the system’s dynamic and is thus to be interpreted
  as an exploration of the environments phase space. To obtain the symmetries we employ
  Koopman theory in which nonlinear dynamics are represented in terms of a linear
  operator acting on the space of measurement functions of the system. We provide
  novel theoretical results on the existence and nature of symmetries relevant for
  control systems such as reinforcement learning settings. Moreover, we empirically
  evaluate our method on several benchmark offline reinforcement learning tasks and
  datasets including D4RL, Metaworld and Robosuite and find that by using our framework
  we consistently improve the state-of-the-art of model-free Q-learning methods.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: weissenbacher22a
month: 0
tex_title: 'Koopman Q-learning: Offline Reinforcement Learning via Symmetries of Dynamics'
firstpage: 23645
lastpage: 23667
page: 23645-23667
order: 23645
cycles: false
bibtex_author: Weissenbacher, Matthias and Sinha, Samarth and Garg, Animesh and Yoshinobu,
  Kawahara
author:
- given: Matthias
  family: Weissenbacher
- given: Samarth
  family: Sinha
- given: Animesh
  family: Garg
- given: Kawahara
  family: Yoshinobu
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
pdf: https://proceedings.mlr.press/v162/weissenbacher22a/weissenbacher22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
