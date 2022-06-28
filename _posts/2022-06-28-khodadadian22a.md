---
title: 'Federated Reinforcement Learning: Linear Speedup Under Markovian Sampling'
booktitle: Proceedings of the 39th International Conference on Machine Learning
abstract: Since reinforcement learning algorithms are notoriously data-intensive,
  the task of sampling observations from the environment is usually split across multiple
  agents. However, transferring these observations from the agents to a central location
  can be prohibitively expensive in terms of the communication cost, and it can also
  compromise the privacy of each agent’s local behavior policy. In this paper, we
  consider a federated reinforcement learning framework where multiple agents collaboratively
  learn a global model, without sharing their individual data and policies. Each agent
  maintains a local copy of the model and updates it using locally sampled data. Although
  having N agents enables the sampling of N times more data, it is not clear if it
  leads to proportional convergence speedup. We propose federated versions of on-policy
  TD, off-policy TD and Q-learning, and analyze their convergence. For all these algorithms,
  to the best of our knowledge, we are the first to consider Markovian noise and multiple
  local updates, and prove a linear convergence speedup with respect to the number
  of agents. To obtain these results, we show that federated TD and Q-learning are
  special cases of a general framework for federated stochastic approximation with
  Markovian noise, and we leverage this framework to provide a unified convergence
  analysis that applies to all the algorithms.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: khodadadian22a
month: 0
tex_title: 'Federated Reinforcement Learning: Linear Speedup Under {M}arkovian Sampling'
firstpage: 10997
lastpage: 11057
page: 10997-11057
order: 10997
cycles: false
bibtex_author: Khodadadian, Sajad and Sharma, Pranay and Joshi, Gauri and Maguluri,
  Siva Theja
author:
- given: Sajad
  family: Khodadadian
- given: Pranay
  family: Sharma
- given: Gauri
  family: Joshi
- given: Siva Theja
  family: Maguluri
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
pdf: https://proceedings.mlr.press/v162/khodadadian22a/khodadadian22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
