---
title: "Persistence-based motif discovery in time series"
authors:
- me
- Charles Truong
- Laurent Oudre

author_notes:

date: "2024-01-01T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["journal"] # conference, journal, preprint, thesis, book, report, dataset, software

# Publication metadata — structured fields used by citation styles and BibTeX export.
publication:
  name: "IEEE Transactions on Knowledge and Data Engineering"
  short_name: "TKDE"
peer_reviewed: true
open_access: true
license: CC-BY-4.0

# Awards, honors, and recognitions. Surfaced as badges on the page and in listings.
# Note: a Test of Time award years after publication uses an explicit `date` that differs from the page date.
awards:


funding:
  - funder: "Région Ile-de-France (DIM MathInnov)"
  - funder: "PhLAMES chair of ENS Paris-Saclay"

abstract: Motif Discovery consists of finding repeated patterns and locating their occurrences in a time series without prior knowledge about their shape or location. Most state-of-the-art algorithms rely on three core parameters, the number of motifs to discover, the length of the motifs, and a similarity threshold between motif occurrences. Setting these parameters is difficult in practice and often results from a trial-and-error strategy. In this paper, we propose a new algorithm that discovers motifs of variable length given a single motif length and without requiring a similarity threshold. At its core, the algorithm maps a time series onto a graph, summarizes it with persistent homology - a tool from topological data analysis - and identifies the most relevant motifs from the graph summary. We propose two versions of the algorithm, one requiring the number of motifs to discover and another, adaptive, that infers the number of motifs from the graph summary. Empirical evaluation on 9 labeled datasets, including 6 real-world datasets, shows that both algorithm versions significantly outperform state-of-the-art algorithms.

# Summary. An optional shortened abstract.
summary: 

tags:

featured: false

hugoblox:
  #ids:
  #  arxiv: arXiv:2605.18276

links:
  - type: pdf
    url: "paper.pdf"
  - type: code
    url: "https://github.com/thibaut-germain/Persistent-Pattern-Discovery"
  - type: link
    url: "https://ieeexplore.ieee.org/abstract/document/10568370"
#  - type: dataset
#    url: ""
#  - type: poster
#    url: ""
#  - type: project
#    url: ""
#  - type: slides
#    url: https://www.slideshare.net/
#  - type: video
#    url: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/projects/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
