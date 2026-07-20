---
title: 'Tensor-SAE: Structured Sparse Autoencoders for Interpretable and Efficient
  Image Representations'
abstract: 'We introduce Tensor-SAE, a structured sparse autoencoder that decodes through
  a learned bank of rank-1 tensor atoms (color $\times$ height $\times$ width). By
  factorizing the decoder into separable color and spatial factors and applying a
  light sparsity prior on latent activations, Tensor-SAE induces compact, interpretable
  representations that enable linear, spatially localized, and semantically meaningful
  interventions in image reconstructions. Unlike unconstrained dense or convolutional
  decoders that distribute information diffusely, Tensor-SAE enforces a strong inductive
  bias that trades some raw pixel-level fidelity for computational efficiency, interpretability,
  and controllability. We evaluate Tensor-SAE on CIFAR-10 against two baselines (a
  parameter-matched Dense-SAE and a ConvAE scaled to match parameter budgets). Our
  empirical suite (six figures) demonstrates that Tensor-SAE: (1) learns low-entropy
  spatial atoms and clean color factors; (2) yields linearly predictable intervention
  effects ($R^2 \approx 0.93$) enabling controllable color edits; (3) achieves superior
  reconstruction efficiency per FLOP and per parameter; (4) produces consistently
  sparse latents; and (5) stabilizes intervention strength during training. We discuss
  trade-offs, limitations, and the application of Tensor-SAE as a building block for
  interpretable, compute-efficient generative systems.'
year: '2026'
openreview: MmpRG8AuHY
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ajay-shastry26a
month: 0
tex_title: 'Tensor-SAE: Structured Sparse Autoencoders for Interpretable and Efficient
  Image Representations'
firstpage: 475
lastpage: 488
page: 475-488
order: 475
cycles: false
bibtex_author: Ajay Shastry, Tanush and Batra, Soham and Patel, Laksh and Lala, Aarav
  and Bae, Andrew and Karuturi, Siddarth and Shah, Mithil and N Shanbhag, Neel
author:
- given: Tanush
  family: Ajay Shastry
- given: Soham
  family: Batra
- given: Laksh
  family: Patel
- given: Aarav
  family: Lala
- given: Andrew
  family: Bae
- given: Siddarth
  family: Karuturi
- given: Mithil
  family: Shah
- given: Neel
  family: N Shanbhag
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
pdf: https://raw.githubusercontent.com/mlresearch/v326/main/assets/ajay-shastry26a/ajay-shastry26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
