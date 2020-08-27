---
title: Regret Bounds for Decentralized Learning in Cooperative Multi-Agent Dynamical
  Systems
abstract: "{Regret analysis is challenging in Multi-Agent Reinforcement Learning (MARL)
  primarily due to the dynamical environments and the decentralized information among
  agents. We attempt to solve this challenge in the context of decentralized learning
  in multi-agent linear-quadratic (LQ) dynamical systems. We begin with a simple setup
  consisting of two agents and two dynamically decoupled stochastic linear systems,
  each system controlled by an agent. The systems are coupled through a quadratic
  cost function. When both systems’ dynamics are unknown and there is no communication
  among the agents, we show that no learning policy can generate sub-linear in $T$
  regret, where $T$ is the time horizon. When only one system’s dynamics are unknown
  and there is one-directional communication from the agent controlling the unknown
  system to the other agent, we propose a MARL algorithm based on the construction
  of an auxiliary single-agent LQ problem. The auxiliary single-agent problem in the
  proposed MARL algorithm serves as an implicit coordination mechanism among the two
  learning agents. This allows the agents to achieve a regret within $O(\\sqrt{T})$
  of the regret of the auxiliary single-agent problem. Consequently, using existing
  results for single-agent LQ regret, our algorithm provides a $\\tilde{O}(\\sqrt{T})$
  regret bound. (Here $\\tilde{O}(\\cdot)$ hides constants and logarithmic factors).
  Our numerical experiments indicate that this bound is matched in practice. From
  the two-agent problem, we extend our results to multi-agent LQ systems with certain
  communication patterns which appear in vehicle platoon control.}"
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: mohammad-asghari20a
month: 0
tex_title: "{Regret Bounds for Decentralized Learning in Cooperative Multi-Agent Dynamical
  Systems}"
firstpage: 121
lastpage: 130
page: 121-130
order: 121
cycles: false
bibtex_author: Mohammad Asghari, Seyed and Ouyang, Yi and Nayyar, Ashutosh
author:
- given: Seyed
  family: Mohammad Asghari
- given: Yi
  family: Ouyang
- given: Ashutosh
  family: Nayyar
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
pdf: http://proceedings.mlr.press/v124/mohammad-asghari20a/mohammad-asghari20a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v124/mohammad-asghari20a/mohammad-asghari20a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
