---
title: Can Graph Foundation Models Generalize Over Architecture?
abstract: 'Graph foundation models (GFMs) have recently attracted interest due to
  the promise of graph neural network (GNN) architectures that generalize zero-shot
  across graphs of arbitrary scales, feature dimensions, and domains. While existing
  work has demonstrated this ability empirically across diverse real-world benchmarks,
  these tasks share a crucial hidden limitation: they admit a narrow set of effective
  GNN architectures. In particular, current domain-agnostic GFMs rely on fixed architectural
  backbones, implicitly assuming that a single message-passing regime suffices across
  tasks. In this paper, we argue that architecture adaptivity is a necessary requirement
  for true GFMs. We show that existing approaches are non-robust to task-dependent
  architectural attributes and, as a case study, use range as a minimal and measurable
  axis along which this limitation becomes explicit. With theoretical analysis and
  controlled synthetic experiments, we demonstrate that fixed-backbone GFMs provably
  under-reach on tasks whose architectural requirements differ from those seen at
  training time. To address this issue, we introduce a framework that adapts effective
  GNN architecture at inference time by discovering and mixing task-specific linear
  graph operators, enabling zero-shot generalization across tasks with heterogeneous
  architectural requirements, without retraining. We validate our approach on arbitrary-range
  synthetic tasks and a suite of real-world benchmarks, demonstrating improved performance
  and robustness over existing domain-agnostic GFMs.'
openreview: wHg1vL9fdO
software: https://github.com/BenGutteridge/GOBLIN
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: gutteridge26a
month: 0
tex_title: "{C}an {G}raph {F}oundation {M}odels {G}eneralize {O}ver {A}rchitecture?"
firstpage: 294
lastpage: 320
page: 294-320
order: 294
cycles: false
bibtex_author: Gutteridge, Benjamin and Bronstein, Michael and Dong, Xiaowen
author:
- given: Benjamin
  family: Gutteridge
- given: Michael
  family: Bronstein
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
pdf: https://raw.githubusercontent.com/mlresearch/v326/main/assets/gutteridge26a/gutteridge26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
