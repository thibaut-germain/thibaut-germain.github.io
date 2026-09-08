---
title: "Time Series Representations with Hard-Coded Invariances"
authors:
  - "me"
  - "Chrysoula Kosma"
  - "Laurent Oudre"
date: "2025-01-01T00:00:00Z"
publishDate: "2025-01-01T00:00:00Z"
publication_types: ["conference"]
publication:
  name: "Forty-second International Conference on Machine Learning"
  short_name: "ICML"
peer_reviewed: true
open_access: true
abstract: >-
  Automatically extracting robust representations from large and complex time series data is becoming imperative for several real-world applications. Unfortunately, the potential of common neural network architectures in capturing invariant properties of time series remains relatively underexplored. For instance, convolutional layers often fail to capture underlying patterns in time series inputs that encompass strong deformations, such as trends. Indeed, invariances to some deformations may be critical for solving complex time series tasks, such as classification, while guaranteeing good generalization performance. To address these challenges, we mathematically formulate and technically design efficient and hard-coded *invariant convolutions* for specific group actions applicable to the case of time series. We construct these convolutions by considering specific sets of deformations commonly observed in time series, including *scaling*, *offset shift*, and *trend*. We further combine the proposed invariant convolutions with standard convolutions in single embedding layers, and we showcase the layer capacity to capture complex invariant time series properties in several scenarios.
summary: 
featured: false
tags: []
hugoblox:
  ids: {}
links:
  - type: pdf
    url: "paper.pdf"
  - type: code
    url: "https://github.com/sissykosm/TS-InvConv"
  - type: link
    url: "https://proceedings.mlr.press/v267/germain25a.html"
projects: []
slides: ""
---
