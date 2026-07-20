---
title: 'Pawsterior: Variational Flow Matching for Structured Simulation-Based Inference'
abstract: We introduce Pawsterior, a variational flow-matching framework for improved
  and extended simulation-based inference (SBI). Many SBI problems involve posteriors
  constrained by structured domains—such as bounded physical parameters or hybrid
  discrete–continuous variables—yet standard flow-matching methods typically operate
  in unconstrained spaces. This mismatch leads to inefficient learning and difficulty
  respecting physical constraints. Our contributions are twofold. First, generalizing
  the geometric inductive bias of CatFlow, we formalize endpoint-induced affine geometric
  confinement, a principle that incorporates domain geometry directly into the inference
  process via a two-sided variational model. This formulation improves numerical stability
  during sampling and leads to consistently better posterior fidelity, as demonstrated
  by improved classifier two-sample test performance across standard SBI benchmarks.
  Second, and more importantly, our variational parameterization enables SBI tasks
  involving discrete latent structure (e.g., switching systems) that are fundamentally
  incompatible with conventional flow-matching approaches. By addressing both geometric
  constraints and discrete latent structure, Pawsterior provides a principled way
  to apply flow-matching in a broader range of structured SBI settings.
openreview: QeiyEvdyVq
software: https://github.com/Carrask0/pawsterior
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: carrasco-pollo26a
month: 0
tex_title: "{P}awsterior: {V}ariational {F}low {M}atching for {S}tructured {S}imulation-{B}ased
  {I}nference"
firstpage: 75
lastpage: 87
page: 75-87
order: 75
cycles: false
bibtex_author: Carrasco-Pollo, Jorge and Eijkelboom, Floor and van de Meent, Jan-Willem
author:
- given: Jorge
  family: Carrasco-Pollo
- given: Floor
  family: Eijkelboom
- given: Jan-Willem
  family: Meent
  prefix: van de
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
pdf: https://raw.githubusercontent.com/mlresearch/v326/main/assets/carrasco-pollo26a/carrasco-pollo26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
