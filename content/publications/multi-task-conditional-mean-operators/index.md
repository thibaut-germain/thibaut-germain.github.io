---
title: "Multi-Task Learning of Conditional Mean Operators: applications to dynamical systems and uncertainty quantification"
authors:
  - "Sami Chemlal"
  - "me"
  - "Rémi Flamary"
  - "Vladimir R. Kostic"
  - "Karim Lounici"
date: "2026-09-28T00:00:00Z"
publishDate: "2026-09-28T00:00:00Z"
publication_types: ["preprint"]
publication:
  name: "arXiv"
  short_name: "arXiv"
peer_reviewed: false
open_access: true
abstract: >-
  Estimating conditional statistics and learning representations of a population of conditional distributions are central problems in many data-driven applications, including uncertainty quantification and dynamical systems analysis. Conditional mean operators (CMOs), a class of linear operators between function spaces, resolve these objectives by providing access to a broad class of conditional statistics. However, existing methods typically estimate each CMO independently or constrain it to prespecified function spaces, thereby preventing the exploitation of shared structure across related distributions. In this work, we posit that related CMOs share finite-dimensional input and output function spaces, and are specialized for each task with a linear operator mapping these spaces. Based on this hypothesis, we introduce MTL-CMO, a multi-task framework that jointly learns shared function spaces and task-specific operators across multiple datasets. We further introduce T-CMO, a transfer learning method that reuses the shared spaces to estimate, in closed form, the operator of a new conditional distribution. We establish statistical guarantees quantifying the benefits of jointly learning the shared function spaces. Our experiments demonstrate that learning shared function spaces improves uncertainty quantification across a broad range of conditional distributions and, when applied to Langevin and plasma dynamics, yields compact representations of complex dynamics that retain physically meaningful information and enable parameter identification.
summary:
featured: false
tags: []
hugoblox:
  ids: {}
links:
  - type: pdf
    url: "paper.pdf"
  - type: link
    url: "https://arxiv.org/abs/2609.35429"
projects: []
slides: ""
---
