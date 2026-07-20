---
title: 'Neurodiversity Meets Colors: Does Position Awareness Destroy Generalization
  in Brain Graph Learning?'
abstract: Graph Neural Networks (GNNs) rely on permutation invariance to exploit symmetries
  in graph data using principles of Geometric Deep Learning. However, in machine learning
  models that process fMRI data using a brain atlas, each node corresponds to a region
  with its own position and neurological function. Thus, permutation invariance would
  make the model unaware of these aspects, causing a significant loss of biological
  interpretability and predictive information. For this reason, many GNN architectures
  opt for assigning each ROI ("Region Of Interest" in the brain) a unique node representation,
  either explicitly or implicitly through feature engineering, before using the graph
  as input for the GNN. In this theoretical study, we investigate the consequences
  of that choice. First, we prove that, if each ROI is explicitly identified with
  a unique color, it is possible to achieve perfect expressivity using a GNN with
  a single max-aggregation message-passing layer, which suffices to attain the maximal
  Rademacher complexity and very loose VC dimension’s bounds. Building on that, we
  derive generalization bounds based on concrete parameters of the model, such as
  ROI embedding dimension and atlas size, revealing ways in which this tradeoff could
  manifest in practice. These findings are particularly relevant in the context of
  fMRI graph learning, where, despite severe struggles with overfitting and data scarcity,
  generalization theory is still underexplored.
openreview: ZNPbn4qp4g
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: angelo-pereira-dantas26a
month: 0
tex_title: 'Neurodiversity Meets Colors: Does Position Awareness Destroy Generalization
  in Brain Graph Learning?'
firstpage: 109
lastpage: 134
page: 109-134
order: 109
cycles: false
bibtex_author: Angelo Pereira Dantas, Matheo and Graziani, Caterina and Sampaio Ferraz
  Ribeiro, Leo and Carvalho, Andre Carlos Ponce de Leon Ferreira De
author:
- given: Matheo
  family: Angelo Pereira Dantas
- given: Caterina
  family: Graziani
- given: Leo
  family: Sampaio Ferraz Ribeiro
- given: Andre Carlos Ponce de Leon Ferreira De
  family: Carvalho
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
pdf: https://raw.githubusercontent.com/mlresearch/v326/main/assets/angelo-pereira-dantas26a/angelo-pereira-dantas26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
