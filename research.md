---
layout: page
title: Projects
---

Here a summarized representation of my work.
For a complete overview, see my [google scholar](https://scholar.google.com/citations?&user=NZmmHacAAAAJ).

### Human-AI Collaboration

More recently, I have focused on formulating and solving human-AI collaborative problems.

**[Modelling Belief-Biased Agents](https://research.aalto.fi/en/publications/more-than-irrational-modeling-belief-biased-agents/) (AAAI)**

Led by [Yifan Zhu](https://yifan-zhu.com), this work considers irrational behavior from human (users) as the rational consequence of imperfect memory.
We propose a user model for such behavior, as well as a sampling mechanism for efficient online inference over its latent variables.

**[Finding Optimal Trade-off in Differential Privacy](https://arxiv.org/abs/2509.04290) (Preprint)**

Led by Yaohong Yang, this work provides an interactive mechanism for finding the optimal differentially private model.
In particular, this simultaneously solves the issue of finding the preferred trade-off between *privacy* and *model performance*, as well as finding the model that optimizes this trade-off.

### Bayesian Reinforcement Learning

During my PhD, most of my work was on the Bayes-adaptive partially observable Markov decision framework - a model-based approach for Bayesian reinforcement learning.
If you are interested in this, I would recommend looking at:

**[Learning in POMDPs with Monte Carlo tree search](https://proceedings.mlr.press/v70/katt17a.html) (ICML)**

A Monte-Carlo tree-search style solution for solving Bayes-adaptive problems.
The particular challenge that is solved in this line of work is on finding (near) optimal solutions despite incredibly large state and belief space.

**[Bayesian Reinforcement Learning in Factored POMDPs](https://par.nsf.gov/biblio/10098819)** and  
**[BADDr: Bayes-Adaptive Deep Dropout RL for POMDPs](https://dl.acm.org/doi/abs/10.5555/3535850.3535932) (AAMAS)**

Bayesian learning of dynamics of the partial observable system using graphical models (first) or Bayesian neural networks (second).
Key contributions here are efficient methods for online inference over the Bayesian posterior.

##### Code

[This repository](https://github.com/sammiekatt/fba-pomdp) contains the C++ code supporting the Bayesian reinforcement learning publications.
Later, when I considered Bayesian neural networks, I moved to [python implementations](https://github.com/sammiekatt/baddr-experiments).
That one combines the (python) libraries on planning and belief tracking in partially observable observation models  with my [library for defining Bayes-adaptive partially observable Markov decision processes](https://github.com/sammiekatt/gbapomdp):

- [Planning in partially observable Markov decision processes](https://github.com/sammiekatt/online-pomdp-planning).
- [Belief tracking in partially observable Markov decision processes](https://github.com/sammiekatt/pomdp-belief-tracking).
