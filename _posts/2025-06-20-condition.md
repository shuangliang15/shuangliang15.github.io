---
layout: post
title:  "Two child problem"
date:   2025-06-20
categories: [Probability]
---

In this blog, all distributions are uniform and all variables are independent. 

A classic problem: A family has two childs. Given that at least one is a boy, what is the probability that both are boys? 

The answer is 1/3, as the condition "at least one is a boy" rules out the girl-girl case. 

<br>

Now consider a variation: A family has two childs. Given that one is a boy born on a Monday, what is the probability that both are boys? 

The answer becomes 13/27, which is larger than 1/3. This can be obtained by (i) looking at the sample space (the product of {boy, girl} and {Seven days in a week}) and (ii) doing the counting. 


<br>

In general, if we change "born on Tuesday" to "falls into a pre-specified category, out of n categories", the probability becomes $\frac{2n-1}{4n-1}$. 

This quantity monotonically increases as n increases, and tends to 1/2 as n tends to infinity. 


<br>

Intuition: For the boy-boy case, the new condition is satisfied if either child falls into the category. Thus, the new condition rules out fewer boy-boy families than it does mixed-gender families. Hence, it increases the conditional probability. 

<br>

More thoughts: The conditioning "there is at least one boy" breaks the symmetry and produces an asymmetrical sample space. Additionally, the set / event "there is at least one boy who is born on Monday" is again asymmetrical (can not be expressed by intersection / union of two marginal events). 

