---
title: Tracking Approximate Solutions of Parameterized Optimization Problems over
  Multi-Dimensional (Hyper-)Parameter Domains
abstract: Many machine learning methods are given as parameterized optimization problems.
  Important examples of such parameters are regularization- and kernel hyperparameters.
  These parameters have to be tuned carefully since the choice of their values can
  have a significant impact on the statistical performance of the learning methods.
  In most cases the parameter space does not carry much structure and parameter tuning
  essentially boils down to exploring the whole parameter space. The case when there
  is only one parameter received quite some attention over the years. First, algorithms
  for tracking an optimal solution for several machine learning optimization problems
  over regularization- and hyperparameter intervals had been developed, but since
  these algorithms can suffer from numerical problems more robust and efficient approximate
  path tracking algorithms have been devised and analyzed recently. By now approximate
  path tracking algorithms are known for regularization-and kernel hyperparameter
  paths with optimal path complexities that depend only on the prescribed approximation
  error. Here we extend the work on approximate path tracking algorithms with approximation
  guarantees to multi-dimensional parameter domains. We show a lower bound on the
  complexity of approximately exploring a multi-dimensional parameter domain that
  is the product of the corresponding path complexities. We also show a matching upper
  bound that can be turned into a theoretically and practically efficient algorithm.
  Experimental results for kernelized support vector machines and the elastic net
  confirm the theoretical complexity analysis.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: blechschmidt15
month: 0
tex_title: Tracking Approximate Solutions of Parameterized Optimization Problems over
  Multi-Dimensional (Hyper-)Parameter Domains
firstpage: 438
lastpage: 447
page: 438-447
sections: 
author:
- given: Katharina
  family: Blechschmidt
- given: Joachim
  family: Giesen
- given: Soeren
  family: Laue
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
pdf: http://proceedings.mlr.press/v37/blechschmidt15.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
