---
title:  "Posterior probability"
mathjax: true
layout: post
---

[Explanation](https://en.wikipedia.org/wiki/Posterior_probability) in wikipeida: 

The posterior probability is a type of conditional probability that results from updating the prior probability with information summarized by the likelihood, through an application of Bayes' theorem.

In variational Bayesian Methods, 

The Posterior Probability: the probability of the parameters $\theta$ given the evidence $X$, and is denoted by $p(\theta|X)$.

The Likelihood Function: $p(X|\theta)$, which is the probability of the evidence given the parameters.

The two are related in this way: 

Given a prior belief that a probability distribution function is $p(\theta)$ and the observations $x$ have a likelihood $p(x|\theta)$, then the posterior probability is defined as $p(\theta|x) = \frac{p(x|\theta)}{p(x)}p(\theta),

where $p_X(x) is the normalizing constant and is caculated as $\p_X(x) = \int p(x|\theta)p(\theta)d\theta$






