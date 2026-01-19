---
title: "Generalized Bayesian additive regression trees for restricted mean survival time inference"
authors:
- admin
- Nicholas C. Henderson

date: "2025-12-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-12-15T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Bayesian Analysis*"
publication_short: "Bayesian Analysis"

abstract: Prediction methods for time-to-event outcomes often utilize survival models that rely on strong assumptions about noninformative censoring or on how individual-level covariates and survival functions are related. When the main interest is in predicting individual-level restricted mean survival times (RMST), reliance on such assumptions can lead to poor predictive performance if these assumptions are not satisfied. We propose a generalized Bayes framework that avoids full probability modeling of all survival outcomes by using an RMST-targeted loss function that depends on a collection of inverse probability of censoring weights (IPCW). In our generalized Bayes formulation, we utilize a flexible additive tree regression model for the RMST function, and the posterior distribution of interest is obtained through model-averaging IPCW-conditional loss function-based pseudo-Bayesian posteriors. Because informative censoring can be captured by the IPCW-dependent loss function, our approach only requires one to specify a model for the censoring distribution, thereby obviating the need for complex joint modeling to handle informative censoring. We evaluate the performance of our method through a series of simulations that compare it with several well-known survival machine learning methods, and we illustrate the application of our method using a multi-site cohort of breast cancer patients with clinical and genomic covariates.

# Summary. An optional shortened abstract.
summary: Prediction methods for time-to-event outcomes often utilize survival models that rely on strong assumptions about noninformative censoring or on how individual-level covariates and survival functions are related. When the main interest is in predicting individual-level restricted mean survival times (RMST), reliance on such assumptions can lead to poor predictive performance if these assumptions are not satisfied. We propose a generalized Bayes framework that avoids full probability modeling of all survival outcomes by using an RMST-targeted loss function that depends on a collection of inverse probability of censoring weights (IPCW). In our generalized Bayes formulation, we utilize a flexible additive tree regression model for the RMST function, and the posterior distribution of interest is obtained through model-averaging IPCW-conditional loss function-based pseudo-Bayesian posteriors. Because informative censoring can be captured by the IPCW-dependent loss function, our approach only requires one to specify a model for the censoring distribution, thereby obviating the need for complex joint modeling to handle informative censoring. We evaluate the performance of our method through a series of simulations that compare it with several well-known survival machine learning methods, and we illustrate the application of our method using a multi-site cohort of breast cancer patients with clinical and genomic covariates.

#tags:
#- Source Themes
featured: true

#links:
 #- name: Custom Link
 # url: https://projecteuclid.org/journals/bayesian-analysis/volume--1/issue--1/Generalized-Bayesian-Additive-Regression-Trees-for-Restricted-Mean-Survival-Time/10.1214/25-BA1579.full
url_pdf: 'https://projecteuclid.org/journalArticle/Download?urlId=10.1214%2F25-BA1579'
url_code: 'https://github.com/mahsaashouri/Loss-Function-BART-RMST'
url_dataset: 'https://github.com/mahsaashouri/Loss-Function-BART-RMST'
url_source: 'https://projecteuclid.org/journals/bayesian-analysis/volume--1/issue--1/Generalized-Bayesian-Additive-Regression-Trees-for-Restricted-Mean-Survival-Time/10.1214/25-BA1579.full'
---
