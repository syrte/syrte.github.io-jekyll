---
title: 'On model assumptions'
date: 2020-02-25
permalink: /posts/2020/02/on-model-assumptions/
tags:
  - statistics
---

This post was originally a part of my response to a referee report
where the referee had asked a few questions related to the assumptions used in our paper.

About the assumptions.

1) Every method comes with its assumptions inevitably.
It is always good to specify the assumptions used explicitly in the text,
We do not claim the assumptions are the "truth", but reasonable approximations.

2) Deviations from the assumptions in application usually 
introduce bias and/or extra systematic uncertainties in the results,
though the effects have not been quantified explicitly in many studies.
If the assumptions are reasonable approximations, then systematic error should be small and ensemble unbiased.
In practice, one can estimate the systematics using realistic mock samples.
The difference between the actual total uncertainty and the statistical uncertainty (the so-called formal error)
is the systematics.
However, it is still possible that such estimated systematics are underestimated,
if the real observation is very atypical compared with the mock sample used.

3) While the the assumptions introduce systematics inevitably,
it can potentially reduce the statistical error thanks to the extra information along with the assumptions.
It is worth making assumptions if the gain in precision is greater than
the loss due to the enlarged systematics.
This is also known as the bias-variance trade-off (bias: systematic uncertainty, variance: statistical uncertainty).
