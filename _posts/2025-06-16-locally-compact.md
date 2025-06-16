---
layout: post
title:  "Locally compactness"
date:   2025-06-16
categories: [Topology]
---

Locally compactness characterizes finite dimensionality. 

Recall that a TVS is said to be locally compact if $0$ has a compact neighborhood.
For a Hausdorff TVS $V$, 

$$
\dim(V)<\infty \Leftrightarrow V \text{ is locally compact}. 
$$

See a proof by [Tao](https://terrytao.wordpress.com/2011/05/24/locally-compact-topological-vector-spaces/). 

<br>
Example: 

In the space $C[0,1]$ with the sup norm, 
consider $\{f_n(x)\}$, where $f_n$ vanishes outside the interval $I_n=[1/n, 1/(n+1)]$, 
takes the value $1$ at the midpoint of $I_n$, and is linearly interpolated within $I_n$. 
Then $\|f_n\|=1$ for all $n$ and $\|f_n-f_m\|=1$ whenever $n\neq m$. 
This implies the unit ball $\|f\|<1$ is not compact. 
