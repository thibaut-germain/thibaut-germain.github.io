---
title: "Geometric Dictionary Learning of Dynamical Systems with Optimal Transport"
authors:
  - "me"
  - "Sami Chemlal"
  - "Rémi Flamary"
  - "Vladimir R. Kostic"
  - "Karim Lounici"
date: "2026-01-01T00:00:00Z"
publishDate: "2026-01-01T00:00:00Z"
publication_types: ["preprint"]
publication:
  name: "arXiv:2605.18276"
  short_name: "arXiv"
peer_reviewed: false
open_access: true
abstract: >-
  Learning dynamical systems through operator-theoretic representations provides a powerful framework for analyzing complex dynamics, as spectral quantities such as eigenvalues and invariant structures encode characteristic time scales and long-term behavior. However, dynamical operators are typically estimated independently for each system, preventing the discovery of shared structure across related dynamics. To address this limitation, we posit that related dynamical systems lie near a low-dimensional manifold in spectral operator space. Based on this hypothesis, we introduce DOODL (Dynamical OperatOr Dictionary Learning), a framework that learns a dictionary of characteristic spectral dynamics whose combinations approximate this manifold and yield compact, interpretable embeddings of individual systems. Beyond representation learning, DOODL enables fast and interpretable operator estimation from short and partially observed trajectories by constraining the estimation to the learned operator manifold. Experiments on metastable Langevin dynamics and turbulent plasma simulations demonstrate that DOODL scales to highly complex multiscale regimes while capturing characteristic spectral structure governing the dynamics rather than merely fitting trajectories, achieving errors one to two orders of magnitude lower than independent operator estimation methods in challenging low-data regimes.
summary: >-
  DOODL learns a dictionary of characteristic spectral dynamics shared across related dynamical systems.
featured: false
tags: []
hugoblox:
  ids: {}
links:
  - type: pdf
    url: "paper.pdf"
  - type: link
    url: "https://arxiv.org/abs/2605.18276"
projects: []
slides: ""
---