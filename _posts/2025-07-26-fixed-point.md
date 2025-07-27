---
layout: post
title:  "Repelling fixed point only attracts null set?"
date:   2025-07-26
categories: [Geometry]
---

Consider a discrete dynamical system $F \colon \mathbb{R}^d\to \mathbb{R}^d$ with a smooth map $F$ and a fixed point $x\in \mathbb{R}^d$. Let 

$$
C=\max_{i} |\lambda_i|, \quad c=\min_{i} |\lambda_i|, 
$$

where $\lambda_i$'s are the eigenvalues of the Jacobian of $F$ at $x$. By the stable manifold theorem <sup>1</sup>, it's clear that:  

* If $1>C$ ($c>1$ resp.), then $x$ attracts (repels resp.) all orbits in a neighborhood. 

* If $C>1$, then locally $x$ repels orbits on the unstable manifold. 

Then an interesting problem is: for the second case, is the basin of attraction $B = \\{ y\colon F^n(y)\to x \\}$ a null set? 

In some cases we have the answers: 

* $JF$ is non-singular everywhere (equivalently,  $F$ is local diffeomorphism): in this case, any orbit that converges to $x$ must enter the local center-stable manifold $W$, whose dimension is less than $d$ and thus a null set, within finite steps (this can be proved using <sup>2</sup>). As $F$ is a submersion everywhere, the preimage of any null set is a null set <sup>3</sup>. Thus, $B\subset \cup_{i}^{\infty} F^{-i}(W)$ is a null set. 

* $JF$ is non-singular almost everywhere: ....

* $JF$ is non-singular on some positive set: Here is a very simple example: let $F(x)=2x$ when $\|x\|<1$, $F(x)=0$ when $\|x\|>2$, and interpolates smoothly on $1\leq \|x\| \leq2$. Then $0$ is locally repelling, but its basin of attraction contains $\\{\|x\|>2\\}$. 


<br>


[1] Theorem 10.14. Robinson, Clark. Dynamical systems: stability, symbolic dynamics, and chaos. 

[2] Theorem III.7. Shub, Michael. Global stability of dynamical systems. 

[3] Theorem 1. Ponomarev, Stanislav P. "Submersions and preimages of sets of measure zero." 

