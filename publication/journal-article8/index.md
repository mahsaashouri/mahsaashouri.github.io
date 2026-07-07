---
title: "Evaluating and Testing for Actionable Treatment Effect Heterogeneity"
authors:
- admin
- Nicholas C. Henderson

date: "2026-07-05T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-07-05T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Statistical Methods in Medical Research*"
publication_short: "Stat Methods Med Res"

abstract: Developing tools for estimating heterogeneous treatment effects (HTE) and individualized treatment effects has been an area of active research in recent years. While these tools have proven to be useful in many contexts, a concern when deploying such methods is the degree to which incorporating HTE into a prediction model provides an advantage over predictive methods which do not allow for variation in treatment effect across individuals. To address this concern, we propose a procedure which evaluates the extent to which an HTE model provides a predictive advantage. Specifically, our procedure targets the gain in predictive performance from using a flexible predictive model incorporating HTE versus an alternative model which is similar to the HTE-utilizing model except that it is constrained to not allow variation in treatment effect. By drawing upon recent work in using nested cross-validation techniques for prediction error inference, we generate confidence intervals for this measure of gain in predictive performance which allows one to directly calculate the level at which one is confident of a substantial HTE-modeling gain in prediction -- a quantity which we refer to as the h-value. Our procedure is generic and can be directly used to assess the benefit of modeling HTE for any method that incorporates treatment effect variation.

# Summary. An optional shortened abstract.
summary: We propose a procedure to evaluate whether incorporating heterogeneous treatment effects (HTE) into a prediction model provides a predictive advantage over models with constant treatment effect. Using nested cross-validation, we generate confidence intervals for this predictive gain and introduce the h-value -- the level at which one is confident of a substantial HTE-modeling gain.

featured: true

url_pdf: 'https://arxiv.org/pdf/2503.04093'
url_code: 'https://github.com/mahsaashouri/HTE-Model-Comparison'
url_dataset: 'https://github.com/mahsaashouri/HTE-Model-Comparison'
url_source: 'https://arxiv.org/abs/2503.04093'
---
