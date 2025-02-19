---
title:  "Stochastic Gradient MCMC"
mathjax: true
layout: post
---


Main Question: How do we sample from a given probability density function ?

The existing method include: 1.inverse transformation. 2. rejection sampling. 3.Markov chain Monte Carlo.

Note: Importance Sampling is not a sampling method

I will introduce a method which can sample from a certain family of probability density functions. I will use the annulus distribution as an example to illustrate this.

For a probability density function, $$p(\mathbf{x})\propto exp(H(\mathbf{x}))$$. We can sample its corresponding random variable $X$ through a stochastic differential equation: 

$$ dx = f( \mathbf{x} )dt + \sqrt{ 2D (\mathbf{x}) } d W_t $$

where $$f(x) = -[ D(\mathbf{x}) + Q(\mathbf{x}) ]\nabla H(\mathbf{x}) + \Gamma(\mathbf{x})$$, $$\Gamma(\mathbf{x}) = -\sum_{j} \frac{\partial}{\partial x_j}( D_{ij}(\mathbf{x}) + Q_{ij}(\mathbf{x}) )$$

Requirement: $$D(\mathbf{x})$$ positive definite, 


