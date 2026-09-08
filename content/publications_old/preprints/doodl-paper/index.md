---
title: "Geometric Dictionary Learning of Dynamical Systems with Optimal Transport"
authors:
- me
- Sami Chemlal
- Rémi Flamary
- Vladimir R. Kostic
- Karim Lounici
author_notes:

date: "2026-05-26T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-05-26T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["preprint"] # conference, journal, preprint, thesis, book, report, dataset, software

# Publication metadata — structured fields used by citation styles and BibTeX export.
publication:
  name: "ArXiv preprint"
  short_name: "ArXiv"


peer_reviewed: False
open_access: true
license: CC-BY-4.0

# Awards, honors, and recognitions. Surfaced as badges on the page and in listings.
# Note: a Test of Time award years after publication uses an explicit `date` that differs from the page date.
awards:


funding:
  - funder: "European Union’s Horizon Europe research and innovation"
    grant: "101120237 (ELIAS)"
  - funder: "Fondation de l’Ecole Polytechnique"
  - funder: "Hi! PARIS"
  - funder: "French National Research Agency"
    grant: "ANR-23-IACL-0005 and ANR-25-PEIA-0005"
  - funder: "NextGenerationEU"
  - funder: "MUR PNRR project PE0000013 CUP J53C22003010006 “Future Artificial Intelligence Research (FAIR)”"

abstract: Learning dynamical systems through operator-theoretic representations provides a powerful framework for analyzing complex dynamics, as spectral quantities such as eigenvalues and invariant structures encode characteristic time scales and long-term behavior. However, dynamical operators are typically estimated independently for each system, preventing the discovery of shared structure across related dynam- ics. To address this limitation, we posit that related dynamical systems lie near a low-dimensional manifold in spectral operator space. Based on this hypothesis, we introduce DOODL (Dynamical OperatOr Dictionary Learning), a framework that learns a dictionary of characteristic spectral dynamics whose combinations ap- proximate this manifold and yield compact, interpretable embeddings of individual systems. Beyond representation learning, DOODL enables fast and interpretable operator estimation from short and partially observed trajectories by constrain- ing the estimation to the learned operator manifold. Experiments on metastable Langevin dynamics and turbulent plasma simulations demonstrate that DOODL scales to highly complex multiscale regimes while capturing characteristic spectral structure governing the dynamics rather than merely fitting trajectories, achieving errors one to two orders of magnitude lower than independent operator estimation methods in challenging low-data regimes.

# Summary. An optional shortened abstract.
summary: 

tags:

featured: false

hugoblox:
  #ids:
  #  arxiv: arXiv:2605.18276

links:
  - type: pdf
    url: http://arxiv.org/pdf/2605.18276v1
  - type: code
    url: ""
  - type: link
    url: "https://arxiv.org/abs/2605.18276"
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
