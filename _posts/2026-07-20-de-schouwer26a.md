---
title: k-Maximum Inner Product Attention for Graph Transformers and the Expressive
  Power of GraphGPS
abstract: 'Graph transformers have shown promise in overcoming limitations of traditional
  graph neural networks, such as oversquashing and difficulties in modelling longrange
  dependencies. However, their application to large-scale graphs is hindered by the
  quadratic memory and computational complexity of the all-to-all attention mechanism.
  Although alternatives such as linearized attention and restricted attention patterns
  have been proposed, these often degrade performance or limit expressive power. To
  better balance efficiency and effectiveness, we introduce k-Maximum Inner Product
  (k-MIP) attention for graph transformers. k-MIP attention selects the most relevant
  key nodes per query via a top-k operation, yielding a sparse yet flexible attention
  pattern. Combined with an attention score computation based on symbolic matrices,
  this results in linear memory complexity and practical speedups of up to an order
  of magnitude compared to all-to-all attention, enabling the processing of graphs
  with over 500k nodes on a single A100 GPU. We provide a theoretical analysis of
  expressive power, showing that k-MIP attention does not compromise the expressiveness
  of graph transformers: specifically, we prove that k-MIP transformers can approximate
  any full-attention transformer to arbitrary precision. In addition, we analyze the
  expressive power of the GraphGPS framework, in which we integrate our attention
  mechanism, and establish an upper bound on its graph distinguishing capability in
  terms of the S-SEG-WL test. Finally, we validate our approach on the Long Range
  Graph Benchmark, the City-Networks benchmark, and two custom large-scale inductive
  point cloud datasets, consistently ranking among the top-performing scalable graph
  transformers.'
openreview: 4Y5kxbH2fI
software: https://github.com/JonasDeSchouwer/k-MIP-Attention-and-the-Expressive-Power-of-GraphGPS
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: de-schouwer26a
month: 0
tex_title: k-{M}aximum {I}nner {P}roduct {A}ttention for {G}raph {T}ransformers and
  the {E}xpressive {P}ower of {G}raphGPS
firstpage: 145
lastpage: 183
page: 145-183
order: 145
cycles: false
bibtex_author: De Schouwer, Jonas and S\'{a}ez de Oc\'{a}riz Borde, Haitz and Dong,
  Xiaowen
author:
- given: Jonas
  family: De Schouwer
- given: Haitz
  family: Ocáriz Borde
  prefix: Sáez de
- given: Xiaowen
  family: Dong
date: 2026-07-20
address:
container-title: 'Proceedings of GRaM: the Second Edition of the Workshop on Geometry-grounded
  Representation Learning and Generative Modeling'
volume: '326'
genre: inproceedings
issued:
  date-parts:
  - 2026
  - 7
  - 20
pdf: https://raw.githubusercontent.com/mlresearch/v326/main/assets/de-schouwer26a/de-schouwer26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
