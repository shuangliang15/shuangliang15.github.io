---
layout: post
title:  "Two child problem"
date:   2025-06-20
categories: [Probability]
---

In this blog, all distributions are uniform and all variables are independent. 

A classic probability problem: A family has two childs. One of them is a boy. What's the probability that both childs are boys? 

The answer is 1/3, as the condition "one of then is a boy" rules out the girl-girl case. 

<br>

Now consider a variation: A family has two childs. One of them is a boy and is born on Monday. What's the probability that both childs are boys? 

The answer becomes 13/27, which is larger than 1/3. This can be obtained by (i) looking at the sample space (the product of {boy, girl} and {Seven days in a week}) and (ii) doing the counting. 

In fact, if we change "born on Tuesday" to "fall into a pre-specified category, out of n categories", the probability turns in to $\frac{2n-1}{4n-1}$. 

This quantity monotonically increases as n increases, and tends to 1/2 as n tends to infinity. 

The intuition is that: comparing to the the two "one boy" cases,  the "boy and boy" case gives one more possibility to let the event "a boy falls into that category" to happen: 
both boys fall in to that category. 
Hence, under the condition "one of the child is a boy and is in that category", the probability of two boys is larger than nothing is provided. 
