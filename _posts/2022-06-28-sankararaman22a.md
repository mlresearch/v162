---
title: 'FITNESS: (Fine Tune on New and Similar Samples) to detect anomalies in streams
  with drift and outliers'
booktitle: Proceedings of the 39th International Conference on Machine Learning
abstract: Technology improvements have made it easier than ever to collect diverse
  telemetry at high resolution from any cyber or physical system, for both monitoring
  and control. In the domain of monitoring, anomaly detection has become an important
  problem in many research areas ranging from IoT and sensor networks to devOps. These
  systems operate in real, noisy and non-stationary environments. A fundamental question
  is then, ‘<em>How to quickly spot anomalies in a data-stream, and differentiate
  them from either sudden or gradual drifts in the normal behaviour?</em>’ Although
  several heuristics have been proposed for detecting anomalies on streams, no known
  method has formalized the desiderata and rigorously proven that they can be achieved.
  We begin by formalizing the problem as a sequential estimation task. We propose
  \name, (\textbf{Fi}ne \textbf{T}une on \textbf{Ne}w and \textbf{S}imilar \textbf{S}amples),
  a flexible framework for detecting anomalies on data streams. We show that in the
  case when the data stream has a gaussian distribution, FITNESS is provably both
  robust and adaptive. The core of our method is to fine-tune the anomaly detection
  system only on recent, similar examples, before predicting an anomaly score. We
  prove that this is sufficient for robustness and adaptivity. We further experimentally
  demonstrate that \name;{is} <em>flexible</em> in practice, i.e., it can convert
  existing offline AD algorithms in to robust and adaptive online ones.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: sankararaman22a
month: 0
tex_title: "{FITNESS}: ({F}ine Tune on New and Similar Samples) to detect anomalies
  in streams with drift and outliers"
firstpage: 19153
lastpage: 19177
page: 19153-19177
order: 19153
cycles: false
bibtex_author: Sankararaman, Abishek and Narayanaswamy, Balakrishnan and Singh, Vikramank
  Y and Song, Zhao
author:
- given: Abishek
  family: Sankararaman
- given: Balakrishnan
  family: Narayanaswamy
- given: Vikramank Y
  family: Singh
- given: Zhao
  family: Song
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
pdf: https://proceedings.mlr.press/v162/sankararaman22a/sankararaman22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
