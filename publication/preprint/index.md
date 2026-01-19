---
title: "Evaluating and testing for actionable treatment effect heterogeneity"
authors:
- admin
- Nicholas Henderson


date: "2025-06-03T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-06-03T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["preprint"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Developing tools for estimating heterogeneous treatment effects (HTE) and individualized treatment effects has been an area of active research in recent years. While these tools have proven to be useful in many contexts, a concern when deploying such methods is the degree to which incorporating HTE into a prediction model provides an advantage over predictive methods which do not allow for variation in treatment effect across individuals. To address this concern, we propose a procedure which evaluates the extent to which an HTE model provides a predictive advantage. Specifically, our procedure targets the gain in predictive performance from using a flexible predictive model incorporating HTE versus an alternative model which is similar to the HTE-utilizing model except that it is constrained to not allow variation in treatment effect. By drawing upon recent work in using nested cross-validation techniques for prediction error inference, we generate confidence intervals for this measure of gain in predictive performance which allows one to directly calculate the level at which one is confident of a substantial HTE-modeling gain in prediction -- a quantity which we refer to as the h-value. Our procedure is generic and can be directly used to assess the benefit of modeling HTE for any method that incorporates treatment effect variation.

# Summary. An optional shortened abstract.
summary: Developing tools for estimating heterogeneous treatment effects (HTE) and individualized treatment effects has been an area of active research in recent years. While these tools have proven to be useful in many contexts, a concern when deploying such methods is the degree to which incorporating HTE into a prediction model provides an advantage over predictive methods which do not allow for variation in treatment effect across individuals. To address this concern, we propose a procedure which evaluates the extent to which an HTE model provides a predictive advantage. Specifically, our procedure targets the gain in predictive performance from using a flexible predictive model incorporating HTE versus an alternative model which is similar to the HTE-utilizing model except that it is constrained to not allow variation in treatment effect. By drawing upon recent work in using nested cross-validation techniques for prediction error inference, we generate confidence intervals for this measure of gain in predictive performance which allows one to directly calculate the level at which one is confident of a substantial HTE-modeling gain in prediction -- a quantity which we refer to as the h-value. Our procedure is generic and can be directly used to assess the benefit of modeling HTE for any method that incorporates treatment effect variation.

#tags:
#- Source Themes
featured: false

#links:
 #- name: Custom Link
 # url: https://arxiv.org/abs/2503.04093
url_pdf: 'https://arxiv.org/pdf/2503.04093'
url_code: 'https://github.com/mahsaashouri/HTE-Model-Comparison'
url_dataset: 'https://github.com/mahsaashouri/HTE-Model-Comparison'
url_source: 'https://arxiv.org/abs/2503.04093'

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example

---
