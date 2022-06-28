---
title: 'VariGrow: Variational Architecture Growing for Task-Agnostic Continual Learning
  based on Bayesian Novelty'
booktitle: Proceedings of the 39th International Conference on Machine Learning
abstract: Continual Learning (CL) is the problem of sequentially learning a set of
  tasks and preserving all the knowledge acquired. Many existing methods assume that
  the data stream is explicitly divided into a sequence of known contexts (tasks),
  and use this information to know when to transfer knowledge from one context to
  another. Unfortunately, many real-world CL scenarios have no clear task nor context
  boundaries, motivating the study of task-agnostic CL, where neither the specific
  tasks nor their switches are known both in training and testing. This paper proposes
  a variational architecture growing framework dubbed VariGrow. By interpreting dynamically
  growing neural networks as a Bayesian approximation, and defining flexible implicit
  variational distributions, VariGrow detects if a new task is arriving through an
  energy-based novelty score. If the novelty score is high and the sample is “detected"
  as a new task, VariGrow will grow a new expert module to be responsible for it.
  Otherwise, the sample will be assigned to one of the existing experts who is most
  “familiar" with it (i.e., one with the lowest novelty score). We have tested VariGrow
  on several CIFAR and ImageNet-based benchmarks for the strict task-agnostic CL setting
  and demonstrate its consistent superior performance. Perhaps surprisingly, its performance
  can even be competitive compared to task-aware methods.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ardywibowo22a
month: 0
tex_title: "{V}ari{G}row: Variational Architecture Growing for Task-Agnostic Continual
  Learning based on {B}ayesian Novelty"
firstpage: 865
lastpage: 877
page: 865-877
order: 865
cycles: false
bibtex_author: Ardywibowo, Randy and Huo, Zepeng and Wang, Zhangyang and Mortazavi,
  Bobak J and Huang, Shuai and Qian, Xiaoning
author:
- given: Randy
  family: Ardywibowo
- given: Zepeng
  family: Huo
- given: Zhangyang
  family: Wang
- given: Bobak J
  family: Mortazavi
- given: Shuai
  family: Huang
- given: Xiaoning
  family: Qian
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
pdf: https://proceedings.mlr.press/v162/ardywibowo22a/ardywibowo22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
