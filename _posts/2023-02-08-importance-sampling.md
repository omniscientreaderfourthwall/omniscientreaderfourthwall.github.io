---
title:  "Posterior probability"
mathjax: true
layout: post
---

[Explanation](https://www.youtube.com/watch?v=V8f8ueBc9sY): 

Importance sampling is a way of calculating the expectation of a certain random variable.

For example, the random variable $Y$ has probability density $g$. And it is hard to compute the expectation directly, because we don't know how to sample it. If I can introduce another easily sampled random variable, I can use that random variable to calculate the expecation. Suppose $U$ is a closed interval [a, b]. Suppose uniform distribution [a, b] has density function f. Note in this case, random variable $Y$ also has support $U$.

$E_p[Y] = \int_U y p(y) dy = \int_U y (p(y)/f(y)) f(y) dy = E_f[y p(y)/f(y)] = E_f[y p(y)(b - a)] $\\

An example of importance sampling:




