---
title: 'Effective Resistance Rewiring: A Simple Topological Correction for Over-Squashing'
abstract: Graph Neural Networks (GNNs) struggle to capture long-range dependencies
  due to over-squashing, where information from exponentially growing neighborhoods
  must pass through a small number of structural bottlenecks. While recent rewiring
  methods attempt to alleviate this limitation, many rely on local criteria such as
  curvature, which can overlook global connectivity bottlenecks that restrict information
  flow. We introduce Effective Resistance Rewiring (ERR), a simple topology correction
  strategy that uses effective resistance as a global signal to detect structural
  bottlenecks. ERR iteratively adds edges between node pairs with the largest resistance
  while removing edges with minimal resistance, strengthening weak communication pathways
  while controlling graph densification through a fixed edge budget. The procedure
  is parameter-free beyond the rewiring budget and relies on a single global measure
  aggregating all paths between node pairs. Beyond evaluating predictive performance
  on GCN model, we analyze how rewiring affects message propagation. By studying cosine
  similarity between node embeddings across layers, we study how the relationship
  between initial node features and learned representations evolves during message
  passing, comparing graphs with and without rewiring. his analysis helps determine
  whether performance gains arise from improved long-range communication. Experiments
  on homophilic (Cora, CiteSeer) and heterophilic (Cornell, Texas) graphs, including
  directed settings with DirGCN, reveal a fundamental trade-off between over-squashing
  and oversmoothing, losing representation diversity across layers. Resistance-guided
  rewiring improves connectivity and signal propagation but can accelerate representation
  mixing in deep models. Combining ERR with normalization techniques (e.g., PairNorm)
  stabilizes this trade-off and improves performance, particularly in heterophilic
  settings.
openreview: thOIyY7WfW
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: miquel-oliver26a
month: 0
tex_title: "{E}ffective {R}esistance {R}ewiring: {A} {S}imple {T}opological {C}orrection
  for {O}ver-{S}quashing"
firstpage: 433
lastpage: 455
page: 433-455
order: 433
cycles: false
bibtex_author: Miquel-Oliver, Bertran and Gil-Sorribes, Manel and Guallar, Victor
  and Molina, Alexis
author:
- given: Bertran
  family: Miquel-Oliver
- given: Manel
  family: Gil-Sorribes
- given: Victor
  family: Guallar
- given: Alexis
  family: Molina
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
pdf: https://raw.githubusercontent.com/mlresearch/v326/main/assets/miquel-oliver26a/miquel-oliver26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
