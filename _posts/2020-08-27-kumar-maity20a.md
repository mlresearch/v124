---
title: High Dimensional Discrete Integration over the Hypergrid
abstract: Recently Ermon et al. (2013) pioneered a way to practically compute approximations
  to large scale counting or discrete integration problems by using random hashes.
  The hashes are used to reduce the counting problem into many separate discrete optimization
  problems. The optimization problems then can be solved by an NP-oracle such as commercial
  SAT solvers or integer linear programming (ILP) solvers. In particular, Ermon et
  al. showed that if the domain of integration is  $\{0,1\}^n$ then it is possible
  to obtain a solution within  a factor of $16$ of the optimal (16-approximation)
  by this technique. In many crucial counting tasks, such as computation of partition
  function of ferromagnetic Potts model, the domain of integration is naturally $\{0,1,…,
  q-1\}^n, q>2$, the hypergrid. The straightforward extension of Ermon et al.’s method
  allows a $q^2$-approximation for this problem. For large values of $q$, this is
  undesirable. In this paper, we show an improved technique to obtain an approximation
  factor of $4+O(1/q^2)$ to this problem. We are able to achieve this by using an
  idea of optimization over multiple bins of the hash functions, that can be easily
  implemented by inequality constraints, or even in unconstrained way. The NP oracle
  in this setting can be simulated by using an ILP solver as in Ermon et. al. We provide
  simulation results to support the theoretical guarantees of our algorithms.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: kumar-maity20a
month: 0
tex_title: High Dimensional Discrete Integration over the Hypergrid
firstpage: 410
lastpage: 419
page: 410-419
order: 410
cycles: false
bibtex_author: Kumar Maity, Raj and Mazumdar, Arya and Pal, Soumyabrata
author:
- given: Raj
  family: Kumar Maity
- given: Arya
  family: Mazumdar
- given: Soumyabrata
  family: Pal
date: 2020-08-27
address: 
container-title: Proceedings of the 36th Conference on Uncertainty in Artificial Intelligence
  (UAI)
volume: '124'
genre: inproceedings
issued:
  date-parts:
  - 2020
  - 8
  - 27
pdf: http://proceedings.mlr.press/v124/kumar-maity20a/kumar-maity20a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v124/kumar-maity20a/kumar-maity20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
