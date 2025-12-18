---
layout: post
title:  "Vanishing velocity in GF"
date:   2025-12-18
categories: [Learning]
---


Consider a general $C^1$, non-negative objective function $L(\theta)$. Use GF to minimize $L$. 
Clearly, $L(\theta\_t)$ converges to a finte value. 

In some settings, we can deduce that $\theta\_t$ stays in a bounded set (e.g., via conservation laws). 
Now, it is true that the velocity $\nabla L(\theta\_t)$ converges to zero, i.e., the trajectory converges to the set of critical points. 

Proof: 

$$L_T-L_0 = \int_0^T \partial_t L_t dt = \int_0^T \langle \nabla L, \partial_t \theta\_t\rangle dt = \int_0^T -\|\partial_t \theta\_t\|^2 dt = \int_0^T -\|\nabla L_t\|^2 dt$$

converges to a finite value. 
So, $\|\nabla L_t\|$ converges to zero. 

<br>

However, it is not always true that $\theta\_t$ converges to a fixed point, which is equivalent to the trajectory length

$$ \int_0^T \| \partial_t \theta\_t \| dt$$ 

converges to a finite value. 

<br>

An illustrative example: $\theta\_t=\sin(\log t)$. Since $\dot{\theta}_t=\cos(\log t) \cdot \frac{1}{t}$, the velocity converges to zero. But the location does not. 
