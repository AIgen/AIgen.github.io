---
title: "Nested conformal prediction and quantile out-of-bag ensemble methods"
collection: "papers"
permalink: /papers/qoob
excerpt: "We provide an alternate view of conformal prediction and leverage it to develop a novel conformal technique that achieves promising results for regression problems."
date: 2019-08-02
venue: 'Under review, Special Issue on Conformal and Probabilistic Prediction with Applications of Pattern Recognition'
paperurl: 'https://arxiv.org/abs/1910.10562'
---

Conformal prediction is a popular tool for distribution-free uncertainty quantification in statistical learning. While the traditional description of conformal prediction starts with a nonconformity score, we provide an alternate (but equivalent) view that starts with a sequence of nested sets and calibrates them to find a valid prediction region. The nested framework easily subsumes all recent score functions including those based on quantile regression and density estimation. While these ideas were originally derived based on sample splitting, our framework seamlessly extends them to leave-one-out techniques like cross-conformal and the jackknife+. We use the framework to derive a new algorithm (QOOB, pronounced cube) that combines four ideas: quantile regression, cross-conformalization, ensemble methods and out-of-bag predictions. In a detailed numerical investigation, QOOB performs either the best or close to the best on all simulated and real datasets.
{: .text-justify}

Links
---
