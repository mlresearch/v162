---
title: Improved StyleGAN-v2 based Inversion for Out-of-Distribution Images
booktitle: Proceedings of the 39th International Conference on Machine Learning
abstract: Inverting an image onto the latent space of pre-trained generators, e.g.,
  StyleGAN-v2, has emerged as a popular strategy to leverage strong image priors for
  ill-posed restoration. Several studies have showed that this approach is effective
  at inverting images similar to the data used for training. However, with out-of-distribution
  (OOD) data that the generator has not been exposed to, existing inversion techniques
  produce sub-optimal results. In this paper, we propose SPHInX (StyleGAN with Projection
  Heads for Inverting X), an approach for accurately embedding OOD images onto the
  StyleGAN latent space. SPHInX optimizes a style projection head using a novel training
  strategy that imposes a vicinal regularization in the StyleGAN latent space. To
  further enhance OOD inversion, SPHInX can additionally optimize a content projection
  head and noise variables in every layer. Our empirical studies on a suite of OOD
  data show that, in addition to producing higher quality reconstructions over the
  state-of-the-art inversion techniques, SPHInX is effective for ill-posed restoration
  tasks while offering semantic editing capabilities.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: subramanyam22a
month: 0
tex_title: Improved {S}tyle{GAN}-v2 based Inversion for Out-of-Distribution Images
firstpage: 20625
lastpage: 20639
page: 20625-20639
order: 20625
cycles: false
bibtex_author: Subramanyam, Rakshith and Narayanaswamy, Vivek and Naufel, Mark and
  Spanias, Andreas and Thiagarajan, Jayaraman J.
author:
- given: Rakshith
  family: Subramanyam
- given: Vivek
  family: Narayanaswamy
- given: Mark
  family: Naufel
- given: Andreas
  family: Spanias
- given: Jayaraman J.
  family: Thiagarajan
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
pdf: https://proceedings.mlr.press/v162/subramanyam22a/subramanyam22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
