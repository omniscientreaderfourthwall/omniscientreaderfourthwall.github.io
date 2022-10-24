---
title:  "Stochastic Gradient MCMC"
mathjax: true
layout: post
---


Main Question: How do we sample from a given probability density function ?

The existing method include: 1.inverse transformation. 2. rejection sampling. 3.Markov chain Monte Carlo.

Note: Importance Sampling is not a sampling method

I will introduce a method which can sample from a certain family of probability density functions.

For a probability density function, $p(\mathbf{x})\propto exp(H(\mathbf{x}))$


