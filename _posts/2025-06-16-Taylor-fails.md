---
layout: post
title:  "Taylor 'fails' for a smooth function"
date:   2025-06-16
categories: [Analysis]
---

Consider $f(x)=\exp(-\frac{1}{x^2})$ with $f(0)=0$. By induction one can verify $f$ is infinitely differentiable everywhere, and at $x=0$, $f^{(k)}(0)=0$ for all $k$. 
Therefore, $f$ cannot be approximated its Taylor expansion of any order. 

Intuition: $f(x)$ is too flat around $x=0$ and satisfies $\lim_{x\rightarrow 0}f(x)x^{-k} = 0$ for all $k$. 
In the Taylor expansion, the remainder is $f$ itself. 
