---
layout: page
title: Projects
---

Here is a brief summary of my work.
For a complete overview, see my [Google Scholar](https://scholar.google.com/citations?&user=NZmmHacAAAAJ).

### Human-AI Collaboration

More recently, I have focused on formulating and solving problems in human-AI collaboration.

**[Modelling Belief-Biased Agents](https://research.aalto.fi/en/publications/more-than-irrational-modeling-belief-biased-agents/) (AAAI)**

Led by [Yifan Zhu](https://yifan-zhu.com), this work models irrational behavior from humans as the rational consequence of imperfect memory.
We propose a user model for this phenomenon, as well as a sampling mechanism for efficient online inference over its latent variables.

**[Finding the Optimal Trade-off in Differential Privacy](https://arxiv.org/abs/2509.04290) (Preprint)**

Led by Yaohong Yang, this work provides an interactive mechanism for finding the optimal differentially private model.
In particular, this simultaneously infers the preferred trade-off between *privacy* and *model performance*, as well as finds the model that optimizes this trade-off.

### Bayesian Reinforcement Learning

During my PhD, most of my work was on the Bayes-adaptive partially observable Markov decision process - a model-based approach for Bayesian reinforcement learning.
If you are interested in this, I recommend looking at:

**[Learning in POMDPs with Monte Carlo tree search](https://proceedings.mlr.press/v70/katt17a.html) (ICML)**

A Monte Carlo tree-search style solution for solving Bayes-adaptive problems.
The particular challenge that is solved in this line of work is finding (near-)optimal solutions despite incredibly large state and belief spaces.

**[Bayesian Reinforcement Learning in Factored POMDPs](https://par.nsf.gov/biblio/10098819)** and 
**[BADDr: Bayes-Adaptive Deep Dropout RL for POMDPs](https://dl.acm.org/doi/abs/10.5555/3535850.3535932) (AAMAS)**

These works focus on Bayesian learning of the dynamics of the partially observable system using graphical models (first) or Bayesian neural networks (second).
Key contributions here are efficient methods for online inference over the Bayesian posterior.

##### Code

[This repository](https://github.com/sammiekatt/fba-pomdp) contains the C++ code supporting the Bayesian reinforcement learning publications.
Later, when I considered Bayesian neural networks, I moved to [Python implementations](https://github.com/sammiekatt/baddr-experiments).
That repository combines the (Python) libraries for planning and belief tracking in partially observable environments with my [library for defining Bayes-adaptive partially observable Markov decision processes](https://github.com/sammiekatt/gbapomdp):

- [Planning in partially observable Markov decision processes](https://github.com/sammiekatt/online-pomdp-planning).
- [Belief tracking in partially observable Markov decision processes](https://github.com/sammiekatt/pomdp-belief-tracking).
