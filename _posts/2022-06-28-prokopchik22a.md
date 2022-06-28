---
title: Nonlinear Feature Diffusion on Hypergraphs
booktitle: Proceedings of the 39th International Conference on Machine Learning
abstract: Hypergraphs are a common model for multiway relationships in data, and hypergraph
  semi-supervised learning is the problem of assigning labels to all nodes in a hypergraph,
  given labels on just a few nodes. Diffusions and label spreading are classical techniques
  for semi-supervised learning in the graph setting, and there are some standard ways
  to extend them to hypergraphs. However, these methods are linear models, and do
  not offer an obvious way of incorporating node features for making predictions.
  Here, we develop a nonlinear diffusion process on hypergraphs that spreads both
  features and labels following the hypergraph structure. Even though the process
  is nonlinear, we show global convergence to a unique limiting point for a broad
  class of nonlinearities and we show that such limit is the global minimum of a new
  regularized semi-supervised learning loss function which aims at reducing a generalized
  form of variance of the nodes across the hyperedges. The limiting point serves as
  a node embedding from which we make predictions with a linear model. Our approach
  is competitive with state-of-the-art graph and hypergraph neural networks, and also
  takes less time to train.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: prokopchik22a
month: 0
tex_title: Nonlinear Feature Diffusion on Hypergraphs
firstpage: 17945
lastpage: 17958
page: 17945-17958
order: 17945
cycles: false
bibtex_author: Prokopchik, Konstantin and Benson, Austin R and Tudisco, Francesco
author:
- given: Konstantin
  family: Prokopchik
- given: Austin R
  family: Benson
- given: Francesco
  family: Tudisco
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
pdf: https://proceedings.mlr.press/v162/prokopchik22a/prokopchik22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
