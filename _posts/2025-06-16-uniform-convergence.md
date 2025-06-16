---
layout: post
title:  "Uniform convergence with diverging derivative"
date:   2025-06-16
categories: [Analysis]
---


There is a sequence of smooth functions that uniformly converge to $0$, while their derivatives diverges everywhere. 

Consider $f_n(x)=\frac{1}{\sqrt{n}} \sin(nx)$. Since $|f_n|_{\infty} = \frac{1}{\sqrt{n}}$, $f_n$ uniformly converges to $0$. However, $f^\prime_n(x)=\sqrt{n}\cos(nx)$ diverges everywhere. 

However, if one treats $f_n$ as distributions, one has $f^\prime_n$ weakly converges to $0$ in $\mathcal{D}^\prime$: for any test function $\phi\in\mathcal{D}$, 

$$\langle f_n^\prime, \phi\rangle = -\langle f_n, \phi^\prime \rangle \rightarrow 0 =\langle0, \phi\rangle.$$

