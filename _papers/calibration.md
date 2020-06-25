---
title: "Distribution-free binary classification: prediction sets, confidence intervals and calibration"
collection: "papers"
permalink: /papers/calibration
excerpt: "We discuss connections between three notions of uncertainty quantification leading to an impossibility result for distribution-free binary classification in certain settings. We complement this with upper bounds for calibration through histogram binning. "
date: 2019-08-02
venue: 'Under review, Neurips 2020'
paperurl: 'https://arxiv.org/abs/2006.10564'
---

We study three notions of uncertainty quantification---calibration, confidence intervals and prediction sets---for binary classification in the distribution-free setting, that is without making any distributional assumptions on the data. With a focus towards calibration, we establish a 'tripod' of theorems that connect these three notions for score-based classifiers. A direct implication is that distribution-free calibration is only possible, even asymptotically, using a scoring function whose level sets partition the feature space into at most countably many sets. Parametric calibration schemes such as variants of Platt scaling do not satisfy this requirement, while nonparametric schemes based on binning do. To close the loop, we derive distribution-free confidence intervals for binned probabilities for both fixed-width and uniform-mass binning. As a consequence of our 'tripod' theorems, these confidence intervals for binned probabilities lead to distribution-free calibration. We also derive extensions to settings with streaming data and covariate shift.
{: .text-justify}

Links
---
