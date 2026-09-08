---
title: "Persistence-based motif discovery in time series"
authors:
  - "me"
  - "Charles Truong"
  - "Laurent Oudre"
date: "2024-01-01T00:00:00Z"
publishDate: "2024-01-01T00:00:00Z"
publication_types: ["journal"]
publication:
  name: "IEEE Transactions on Knowledge and Data Engineering"
  short_name: "TKDE"
peer_reviewed: true
open_access: true
abstract: >-
  Motif Discovery consists of finding repeated patterns and locating their occurrences in a time series without prior knowledge about their shape or location. Most state-of-the-art algorithms rely on three core parameters: the number of motifs to discover, the length of the motifs, and a similarity threshold between motif occurrences. Setting these parameters is difficult in practice and often results from a trial-and-error strategy. In this paper, we propose a new algorithm that discovers motifs of variable length given a single motif length and without requiring a similarity threshold. At its core, the algorithm maps a time series onto a graph, summarizes it with persistent homology - a tool from topological data analysis - and identifies the most relevant motifs from the graph summary. We propose two versions of the algorithm, one requiring the number of motifs to discover and another, adaptive, that infers the number of motifs from the graph summary. Empirical evaluation on 9 labeled datasets, including 6 real-world datasets, shows that both algorithm versions significantly outperform state-of-the-art algorithms.
summary: 
featured: false
tags: []
hugoblox:
  ids: {}
links:
  - type: pdf
    url: "paper.pdf"
  - type: code
    url: "https://github.com/thibaut-germain/Persistent-Pattern-Discovery"
  - type: link
    url: "https://ieeexplore.ieee.org/abstract/document/10568370"
projects: []
slides: ""
---
