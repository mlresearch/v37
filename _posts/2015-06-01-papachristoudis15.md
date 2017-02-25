---
supplementary: Supplementary:papachristoudis15-supp.pdf
title: Adaptive Belief Propagation
abstract: Graphical models are widely used in inference problems. In practice, one
  may construct a single large-scale model to explain a phenomenon of interest, which
  may be utilized in a variety of settings. The latent variables of interest, which
  can differ in each setting, may only represent a small subset of all variables.
  The marginals of variables of interest may change after the addition of measurements
  at different time points. In such adaptive settings, naive algorithms, such as standard
  belief propagation (BP), may utilize many unnecessary computations by propagating
  messages over the entire graph. Here, we formulate an efficient inference procedure,
  termed adaptive BP (AdaBP), suitable for adaptive inference settings. We show that
  it gives exact results for trees in discrete and Gaussian Markov Random Fields (MRFs),
  and provide an extension to Gaussian loopy graphs. We also provide extensions on
  finding the most likely sequence of the entire latent graph. Lastly, we compare
  the proposed method to standard BP and to that of (Sumer et al., 2011), which tackles
  the same problem. We show in synthetic and real experiments that it outperforms
  standard BP by orders of magnitude and explore the settings that it is advantageous
  over (Sumer et al., 2011).
layout: inproceedings
series: Proceedings of Machine Learning Research
id: papachristoudis15
month: 0
tex_title: Adaptive Belief Propagation
firstpage: 899
lastpage: 907
page: 899-907
sections: 
author:
- given: Georgios
  family: Papachristoudis
- given: John
  family: Fisher
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
pdf: http://proceedings.mlr.press/v37/papachristoudis15.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
