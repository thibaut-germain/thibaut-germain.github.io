---
title: "Shape analysis for time series"
authors:
  - "me"
  - "Samuel Gruffaz"
  - "Charles Truong"
  - "Laurent Oudre"
  - "Alain Durmus"
date: "2024-01-01T00:00:00Z"
publishDate: "2024-01-01T00:00:00Z"
publication_types: ["conference"]
publication:
  name: "Advances in Neural Information Processing Systems 37"
  short_name: "NeurIPS"
peer_reviewed: true
open_access: true
abstract: >-
  Analyzing inter-individual variability of physiological functions is particularly appealing in medical and biological contexts to describe or quantify health conditions. Such analysis can be done by comparing individuals to a reference one with time series as biomedical data. This paper introduces an unsupervised representation learning (URL) algorithm for time series tailored to inter-individual studies. The idea is to represent time series as deformations of a reference time series. The deformations are diffeomorphisms parameterized and learned by our method called TS-LDDMM. Once the deformations and the reference time series are learned, the vector representations of individual time series are given by the parametrization of their corresponding deformation. At the crossroads between URL for time series and shape analysis, the proposed algorithm handles irregularly sampled multivariate time series of variable lengths and provides shape-based representations of temporal data. In this work, we establish a representation theorem for the graph of a time series and derive its consequences on the LDDMM framework. We showcase the advantages of our representation compared to existing methods using synthetic data and real-world examples motivated by biomedical applications.
summary:
featured: false
tags: []
hugoblox:
  ids: {}
links:
  - type: pdf
    url: "paper.pdf"
  - type: code
    url: "https://github.com/thibaut-germain/TSLDDMM"
  - type: package
    url: "https://samuelgruffaz.github.io/PCA_for_time_series/"
  - type: link
    url: "https://proceedings.neurips.cc/paper_files/paper/2024/hash/ad86418f7bdfa685cd089e028efd75cd-Abstract-Conference.html"
projects: []
slides: ""
---
