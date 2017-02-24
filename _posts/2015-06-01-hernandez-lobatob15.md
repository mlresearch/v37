---
supplementary: Supplementary:hernandez-lobatob15-supp.pdf
title: Predictive Entropy Search for Bayesian Optimization with Unknown Constraints
abstract: Unknown constraints arise in many types of expensive black-box optimization
  problems. Several methods have been proposed recently for performing Bayesian optimization
  with constraints, based on the expected improvement (EI) heuristic. However, EI
  can lead to pathologies when used with constraints. For example, in the case of
  decoupled constraints—i.e., when one can independently evaluate the objective or
  the constraints—EI can encounter a pathology that prevents exploration. Additionally,
  computing EI requires a current best solution, which may not exist if none of the
  data collected so far satisfy the constraints. By contrast, information-based approaches
  do not suffer from these failure modes. In this paper, we present a new information-based
  method called Predictive Entropy Search with Constraints (PESC). We analyze the
  performance of PESC and show that it compares favorably to EI-based approaches on
  synthetic and benchmark problems, as well as several real-world examples. We demonstrate
  that PESC is an effective algorithm that provides a promising direction towards
  a unified solution for constrained Bayesian optimization.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: hernandez-lobatob15
month: 0
firstpage: 1699
lastpage: 1707
page: 1699-1707
sections: 
author:
- given: Jose Miguel
  family: Hernandez-Lobato
- given: Michael
  family: Gelbart
- given: Matthew
  family: Hoffman
- given: Ryan
  family: Adams
- given: Zoubin
  family: Ghahramani
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
pdf: http://proceedings.mlr.press/v37/hernandez-lobatob15/hernandez-lobatob15.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
