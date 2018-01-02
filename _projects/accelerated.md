---
title: "Accelerating Iterative Hard Thresholding methods"
excerpt: "Faster algorithms for optimization problems with L0 (sparsity) constraints."
collection: "projects"
permalink: /projects/accelerated
date: 2017-12-22
---

We are interested in efficient algorithms for solving constrained optimization problems with L0 (sparsity) constraints. For instance, consider the **sparse linear regression** problem: basically standard least squares but with fewer data-points than the dimension. 

One of the algorithms for this is to alternatingly perform a gradient descent and a thresholding step. This is called Iterative Hard Thresholding (IHT). We propose a new algorithm for IHT which performs accelerated gradient descent instead of vanilla gradient descent. We are looking to prove guarantees for this algorithm. 
{: .text-justify}

Links
---
[On Iterative Hard Thresholding Methods for High-dimensional M-Estimation. Prateek Jain, Ambuj Tewari, Purushottam Kar.](https://arxiv.org/abs/1410.5137)