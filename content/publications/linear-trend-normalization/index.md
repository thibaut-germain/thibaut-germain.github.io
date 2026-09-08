---
title: "Linear-trend normalization for multivariate subsequence similarity search"
authors:
  - "me"
  - "Charles Truong"
  - "Laurent Oudre"
date: "2024-01-01T00:00:00Z"
publishDate: "2024-01-01T00:00:00Z"
publication_types: ["conference"]
publication:
  name: "2024 IEEE 40th International Conference on Data Engineering Workshops (ICDEW), 167–175"
  short_name: "ICDEW"
peer_reviewed: true
open_access: false
abstract: >-
  Finding repeating or anomalous subsequences in long time series is a crucial task in numerous data analysis pipelines. Most of those methods share a common step where they compute the pairwise similarity between all subsequences of a time series or between a fixed subsequence and a time series. However, the presence of a trend in a time series may cause changes in the shape of subsequences, making the similarity measure less reliable. This article introduces a new normalization scheme called LT-normalization (for Linear Trend) to prevent this phenomenon. It generalizes the well-known Z-normalization by removing the linear trend and scaling the subsequences to unit variance. Like the Z-normalization, we show that the LT-normalization has a computationally efficient recursive formulation. Thanks to this recursion property, the LT-normalized matrix profile can be computed with the same quadratic complexity as the classical Z-normalized matrix profile. Our procedure can naturally cope with multivariate signals. Empirical results on synthetic and real datasets show that the LT-normalized matrix profile has competitive performances for the best motif pair, similarity search, and motif set discovery problems.
summary: 
featured: false
tags: []
hugoblox:
  ids: {}
links:
  - type: link
    url: "https://ieeexplore.ieee.org/abstract/document/10555089"
  - type: code
    url: "https://github.com/thibaut-germain/lt-normalized"
projects: []
slides: ""
---
