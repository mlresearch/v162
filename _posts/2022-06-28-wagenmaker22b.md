---
title: Reward-Free RL is No Harder Than Reward-Aware RL in Linear Markov Decision
  Processes
booktitle: Proceedings of the 39th International Conference on Machine Learning
abstract: Reward-free reinforcement learning (RL) considers the setting where the
  agent does not have access to a reward function during exploration, but must propose
  a near-optimal policy for an arbitrary reward function revealed only after exploring.
  In the the tabular setting, it is well known that this is a more difficult problem
  than reward-aware (PAC) RL—where the agent has access to the reward function during
  exploration—with optimal sample complexities in the two settings differing by a
  factor of $|\mathcal{S}|$, the size of the state space. We show that this separation
  does not exist in the setting of linear MDPs. We first develop a computationally
  efficient algorithm for reward-free RL in a $d$-dimensional linear MDP with sample
  complexity scaling as $\widetilde{\mathcal{O}}(d^2 H^5/\epsilon^2)$. We then show
  a lower bound with matching dimension-dependence of $\Omega(d^2 H^2/\epsilon^2)$,
  which holds for the reward-aware RL setting. To our knowledge, our approach is the
  first computationally efficient algorithm to achieve optimal $d$ dependence in linear
  MDPs, even in the single-reward PAC setting. Our algorithm relies on a novel procedure
  which efficiently traverses a linear MDP, collecting samples in any given “feature
  direction”, and enjoys a sample complexity scaling optimally in the (linear MDP
  equivalent of the) maximal state visitation probability. We show that this exploration
  procedure can also be applied to solve the problem of obtaining “well-conditioned”
  covariates in linear MDPs.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: wagenmaker22b
month: 0
tex_title: Reward-Free {RL} is No Harder Than Reward-Aware {RL} in Linear {M}arkov
  Decision Processes
firstpage: 22430
lastpage: 22456
page: 22430-22456
order: 22430
cycles: false
bibtex_author: Wagenmaker, Andrew J and Chen, Yifang and Simchowitz, Max and Du, Simon
  and Jamieson, Kevin
author:
- given: Andrew J
  family: Wagenmaker
- given: Yifang
  family: Chen
- given: Max
  family: Simchowitz
- given: Simon
  family: Du
- given: Kevin
  family: Jamieson
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
pdf: https://proceedings.mlr.press/v162/wagenmaker22b/wagenmaker22b.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
