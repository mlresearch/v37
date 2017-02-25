---
supplementary: Supplementary:narasimhana15-supp.pdf
title: 'Optimizing Non-decomposable Performance Measures: A Tale of Two Classes'
abstract: Modern classification problems frequently present mild to severe label imbalance
  as well as specific requirements on classification characteristics, and require
  optimizing performance measures that are non-decomposable over the dataset, such
  as F-measure. Such measures have spurred much interest and pose specific challenges
  to learning algorithms since their non-additive nature precludes a direct application
  of well-studied large scale optimization methods such as stochastic gradient descent.
  In this paper we reveal that for two large families of performance measures that
  can be expressed as functions of true positive/negative rates, it is indeed possible
  to implement point stochastic updates. The families we consider are concave and
  pseudo-linear functions of TPR, TNR which cover several popularly used performance
  measures such as F-measure, G-mean and H-mean. Our core contribution is an adaptive
  linearization scheme for these families, using which we develop optimization techniques
  that enable truly point-based stochastic updates. For concave performance measures
  we propose SPADE, a stochastic primal dual solver; for pseudo-linear measures we
  propose STAMP, a stochastic alternate maximization procedure. Both methods have
  crisp convergence guarantees, demonstrate significant speedups over existing methods
  - often by an order of magnitude or more, and give similar or more accurate predictions
  on test data.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: narasimhana15
month: 0
tex_title: 'Optimizing Non-decomposable Performance Measures: A Tale of Two Classes'
firstpage: 199
lastpage: 208
page: 199-208
sections: 
author:
- given: Harikrishna
  family: Narasimhan
- given: Purushottam
  family: Kar
- given: Prateek
  family: Jain
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
pdf: http://proceedings.mlr.press/v37/narasimhana15.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
