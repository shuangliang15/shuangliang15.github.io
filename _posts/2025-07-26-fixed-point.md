---
layout: post
title:  "Repelling directions -> measure-zero attraction basin?"
date:   2025-07-26
categories: [Geometry]
---

Consider a discrete dynamical system $F \colon \mathbb{R}^d\to \mathbb{R}^d$ with a smooth map $F$ and a fixed point $x\in \mathbb{R}^d$. 

Let $\lambda_i$'s be the eigenvalues of the Jacobian of $F$ at $x$. When $\max_{i} \mid \lambda_i \mid > 1$, $x$ has repelling directions. I.e., locally $x$ repels orbits along the unstable manifold. 

<br>

An interesting problem: is the basin of attraction $B(x) = \\{ y\colon F^n(y)\to x \\}$ always a null set? 

* When $F$'s singular points form a positive measure set, the statement is incorrect. One can just let $F$ be a constant map to $x_0$ on regions far away from $x_0$. 

* When $F$'s singular points form a measure zero set, this is (almost) always true. Specifically, [1] provided the following theorem (rephrased)

> Consider $f\in C^{\infty}(\mathbb{R}^{d}, \mathbb{R}^{d})$ and $S$ consisting of fixed points that have at least one repelling direction. Assume that $\{\det Jf =0 \}$ is a measure zero set, and that $Jf$ is symmetric on $S$. Then, $B(S)$ is a measure zero set. 

<br>

An example: let $f$ be the gradient descent update map on a polynomial loss $f(x)=x-\eta \nabla L(x)$. Note in this case, $\det Jf$ is a polynomial; so as long as there is one $x_0$ such that $JF(x_0)$ has full rank, the first condition is satisfied. Meanwhile, $JF=I-\eta \nabla^2 L$ is always symmetry as $L$ is smooth. 

<br>

[1] Cheridito, Patrick, Arnulf Jentzen, and Florian Rossmannek. "Gradient descent provably escapes saddle points in the training of shallow ReLU networks." Journal of Optimization Theory and Applications 203.3 (2024): 2617-2648. 
