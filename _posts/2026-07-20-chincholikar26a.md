---
title: Towards Text-Line Segmentation of Historical Documents Using Graph Neural Networks
abstract: 'We present an initial investigation into a graph-based problem formulation
  for performing text-line segmentation of historical documents, by representing characters
  (or grapheme clusters) as the nodes, and with edges connecting characters to their
  previous and next characters on the text-line. This converts the image segmentation
  learning task into a binary edge classification learning task. This also enables
  training on large-scale synthetic data simulating complex layouts, enabling better
  robustness to Layout-level distribution shifts observed in historical documents.
  Furthermore, we introduce a benchmark dataset of 15 Sanskrit manuscripts with diverse
  layouts. We propose a method based on CRAFT and Graph Neural Networks (GNNs), which
  uses geometric priors of text-lines to perform competitively with leading approaches
  in zero-shot and few-shot experimental settings on the Sanskrit dataset introduced
  and the U-DIADS-TL dataset. The proposed method further demonstrates competitive
  accuracy and better consistency than leading methods Doc-UFCN and SeamFormer when
  evaluating robustness to distribution shifts over increasing data sizes (using intra-manuscript
  and inter-manuscript train-test data splits) on the Sanskrit dataset introduced
  and the DIVA-HisDB dataset. Finally, we demonstrate that the proposed method achieves
  strong performance in the downstream, goal-oriented evaluation of text recognized
  from the segmented text-lines. The dataset, training, and inference code is available
  at: https://github.com/flame-cai/gnn-synthetic-layout-historical/tree/gram-submission'
openreview: 0GoutqIh3l
software: https://github.com/flame-cai/gnn-synthetic-layout-historical
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chincholikar26a
month: 0
tex_title: "{T}owards {T}ext-Line {S}egmentation of {H}istorical {D}ocuments Using
  {G}raph {N}eural {N}etworks"
firstpage: 88
lastpage: 108
page: 88-108
order: 88
cycles: false
bibtex_author: Chincholikar, Kartik and Gopalan, Kaushik and Hasabnis, Mihir
author:
- given: Kartik
  family: Chincholikar
- given: Kaushik
  family: Gopalan
- given: Mihir
  family: Hasabnis
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
pdf: https://raw.githubusercontent.com/mlresearch/v326/main/assets/chincholikar26a/chincholikar26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
