---
title: 'MASSIVE: Tractable and Robust Bayesian Learning of Many-Dimensional Instrumental
  Variable Models'
abstract: The recent availability of huge, many-dimensional data sets, like those
  arising from genome-wide association studies (GWAS), provides many opportunities
  for strengthening causal inference. One popular approach is to utilize these many-dimensional
  measurements as instrumental variables (instruments) for improving the causal effect
  estimate between other pairs of variables. Unfortunately, searching for proper instruments
  in a many-dimensional set of candidates is a daunting task due to the intractable
  model space and the fact that we cannot directly test which of these candidates
  are valid, so most existing search methods either rely on overly stringent modeling
  assumptions or fail to capture the inherent model uncertainty in the selection process.
  We show that, as long as at least some of the candidates are (close to) valid, without
  knowing a priori which ones, they collectively still pose enough restrictions on
  the target interaction to obtain a reliable causal effect estimate. We propose a
  general and efficient causal inference algorithm that accounts for model uncertainty
  by performing Bayesian model averaging over the most promising many-dimensional
  instrumental variable models, while at the same time employing weaker assumptions
  regarding the data generating process. We showcase the efficiency, robustness and
  predictive performance of our algorithm through experimental results on both simulated
  and real-world data.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: gabriel-bucur20a
month: 0
tex_title: 'MASSIVE: Tractable and Robust Bayesian Learning of Many-Dimensional Instrumental
  Variable Models'
firstpage: 1049
lastpage: 1058
page: 1049-1058
order: 1049
cycles: false
bibtex_author: Gabriel Bucur, Ioan and Claassen, Tom and Heskes, Tom
author:
- given: Ioan
  family: Gabriel Bucur
- given: Tom
  family: Claassen
- given: Tom
  family: Heskes
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
pdf: http://proceedings.mlr.press/v124/gabriel-bucur20a/gabriel-bucur20a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v124/gabriel-bucur20a/gabriel-bucur20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
