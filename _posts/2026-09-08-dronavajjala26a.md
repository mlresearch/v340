---
title: Decision-Informed Online Conformal Prediction for ICU Resource Allocation
abstract: 'Hospitals allocate scarce ICU resources—nurses, beds, discharge slots—using
  predictions of patient length of stay (LOS), but prediction errors under shifting
  patient populations lead to costly misallocations. Online conformal prediction provides
  adaptive uncertainty sets that track a target coverage rate (e.g., 90%) without
  distributional assumptions, but the resulting robust decisions incur a Price of
  Coverage—the excess cost of hedging against uncertainty. We observe that standard
  conformal methods distribute uncertainty budgets uniformly, including on resources
  the optimizer assigns to minimum levels. We propose Decision-Informed Conformal
  Adaptation (DICA), which uses the downstream optimization’s resource allocation
  as feedback to reshape uncertainty margins: tighter where allocation is minimal
  (saving cost), wider where allocation is high (strengthening protection). DICA preserves
  the same adaptive quantile update and scalar coverage tracking as standard online
  conformal; the reshaped radii do not carry a formal per-component guarantee, but
  decision-level analysis shows that coverage misses are confined to lower-bound dimensions
  where their clinical cost is negligible. Across 328K patient stays from three real
  clinical datasets (MIMIC-IV, eICU, and a general hospital cohort), DICA reduces
  the Price of Coverage by 43–54% relative to uniform conformal while maintaining
  approximately 90% coverage. Under chronological patient ordering, static calibration
  methods degrade to 78–86% coverage, while online conformal methods remain near the
  target rate.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: dronavajjala26a
month: 0
tex_title: Decision-Informed Online Conformal Prediction for ICU Resource Allocation
firstpage: 410
lastpage: 434
page: 410-434
order: 410
cycles: false
bibtex_author: Dronavajjala, Chandra
author:
- given: Chandra
  family: Dronavajjala
date: 2026-09-08
address:
container-title: Proceedings of the 11th Machine Learning for Healthcare Conference
volume: '340'
genre: inproceedings
issued:
  date-parts:
  - 2026
  - 9
  - 8
pdf: https://raw.githubusercontent.com/mlresearch/v340/main/assets/dronavajjala26a/dronavajjala26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
