---
title: Survival Analysis with Limited Overlap and Censoring Distribution Shift
abstract: 'Survival analysis methods are often used to predict the time until the
  onset of an event in settings when the true time-to-event (TTE) may be censored
  during training. Such approaches typically assume uncensored data are representative
  of censored data and that the probability of censoring conditioned on the covariates
  remains constant over time, i.e., there is no censoring distribution shift. However,
  both assumptions can fail in practice when censoring results from interventions
  targeted to individuals with particular comorbidities or genetic markers (such as
  prophylactic surgery when predicting time to cancer onset, or scheduled cesarean
  delivery and induction when predicting time to spontaneous labor) and changes in
  clinical policies alter which individuals are targeted for these interventions over
  time. To address this, we propose a new approach, cluster-weighted inference of
  time-to-event (CWITE), that remains accurate when these assumptions do not hold.
  Unlike existing approaches that ignore times-to-censoring (TTC) or treat them only
  as a lower bound of the TTE, CWITE leverages the insight that a subset of censored
  individuals are likely censored close to their true TTEs, and uses a novel mechanism
  to learn from such individuals. On the task of predicting time to spontaneous labor
  using real-world data, CWITE improves TTE accuracy for individuals similar to censored
  training data (mean absolute error: 6.50 days, 95% CI: [5.55, 7.40] vs. 7.82 days,
  [6.82, 8.82]) while maintaining comparable performance for those similar to uncensored
  training data (6.50 days, [5.54, 7.61] vs. 6.63 days, [5.67, 7.69]). Our results
  demonstrate that incorporating more specific supervision from censored training
  data can significantly improve TTE predictions in settings with limited overlap
  and censoring distribution shift, challenges common in real-world clinical data.
  Code to implement CWITE and reproduce all experiments in the paper is available
  at https://github.com/MLD3/CWITE.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: krishnamoorthy26a
month: 0
tex_title: Survival Analysis with Limited Overlap and Censoring Distribution Shift
firstpage: 913
lastpage: 947
page: 913-947
order: 913
cycles: false
bibtex_author: Krishnamoorthy, Meera and Tjandra, Donna and Shanmugam, Divya M and
  Kowalski, Amanda E. and Wiens, Jenna
author:
- given: Meera
  family: Krishnamoorthy
- given: Donna
  family: Tjandra
- given: Divya M
  family: Shanmugam
- given: Amanda E.
  family: Kowalski
- given: Jenna
  family: Wiens
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
pdf: https://raw.githubusercontent.com/mlresearch/v340/main/assets/krishnamoorthy26a/krishnamoorthy26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
