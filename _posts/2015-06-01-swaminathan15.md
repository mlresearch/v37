---
title: 'Counterfactual Risk Minimization: Learning from Logged Bandit Feedback'
abstract: We develop a learning principle and an efficient algorithm for batch learning
  from logged bandit feedback. This learning setting is ubiquitous in online systems
  (e.g., ad placement, web search, recommendation), where an algorithm makes a prediction
  (e.g., ad ranking) for a given input (e.g., query) and observes bandit feedback
  (e.g., user clicks on presented ads). We first address the counterfactual nature
  of the learning problem through propensity scoring. Next, we prove generalization
  error bounds that account for the variance of the propensity-weighted empirical
  risk estimator. These constructive bounds give rise to the Counterfactual Risk Minimization
  (CRM) principle. We show how CRM can be used to derive a new learning method – called
  Policy Optimizer for Exponential Models (POEM) – for learning stochastic linear
  rules for structured output prediction. We present a decomposition of the POEM objective
  that enables efficient stochastic gradient optimization. POEM is evaluated on several
  multi-label classification problems showing substantially improved robustness and
  generalization performance compared to the state-of-the-art.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: swaminathan15
month: 0
firstpage: 814
lastpage: 823
page: 814-823
sections: 
author:
- given: Adith
  family: Swaminathan
- given: Thorsten
  family: Joachims
date: 2015-06-01
address: Lille, France
publisher: PMLR
container-title: Proceedings of the 32nd International Conference on Machine Learning
volume: '37'
genre: inproceedings
issued:
  date-parts:
  - 2015
  - 6
  - 1
pdf: http://proceedings.mlr.press/v37/swaminathan15.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
