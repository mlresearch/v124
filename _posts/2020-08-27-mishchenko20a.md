---
title: 99% of Worker-Master Communication in Distributed Optimization Is Not Needed
abstract: "{In this paper we discuss sparsification of worker-to-server communication
  in large distributed systems. We improve upon algorithms that fit the following
  template: a local gradient estimate is computed independently by each worker, then
  communicated to a master, which subsequently performs averaging. The average is
  broadcast back to the workers, which use it to perform a gradient-type step to update
  the local version of the model. We observe that the above template is fundamentally
  inefficient in that too much data is unnecessarily communicated from the workers
  to the server, which slows down the overall system. We propose a fix based on a
  new update-sparsification method we develop in this work, which we suggest be used
  on top of existing methods. Namely, we develop a new variant of parallel block coordinate
  descent based on independent sparsification of the local gradient estimates before
  communication. We demonstrate that with only $m/n$ blocks sent by each of $n$ workers,
  where $m$ is the total number of parameter blocks, the theoretical iteration complexity
  of the underlying distributed methods is essentially unaffected. As an illustration,
  this means that when $n=100$ parallel workers are used, the communication of 99%
  blocks is redundant, and hence a waste of time. Our theoretical claims are supported
  through extensive numerical experiments which demonstrate an almost perfect match
  with our theory on a number of synthetic and real datasets.}"
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: mishchenko20a
month: 0
tex_title: "{99% of Worker-Master Communication in Distributed Optimization Is Not
  Needed}"
firstpage: 979
lastpage: 988
page: 979-988
order: 979
cycles: false
bibtex_author: Mishchenko, Konstantin and Hanzely, Filip and Richtarik, Peter
author:
- given: Konstantin
  family: Mishchenko
- given: Filip
  family: Hanzely
- given: Peter
  family: Richtarik
date: 2020-08-27
address: 
container-title: "{Proceedings of the 36th Conference on Uncertainty in Artificial
  Intelligence (UAI)}"
volume: '124'
genre: inproceedings
issued:
  date-parts:
  - 2020
  - 8
  - 27
pdf: http://proceedings.mlr.press/v124/mishchenko20a/mishchenko20a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v124/mishchenko20a/mishchenko20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
