---
title: 'A Spectral-Grassmann Wasserstein metric for operator representations of dynamical systems'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - me
  - Rémi Flamary
  - Vladimir R. Kostic
  - Karim Lounici

# Author notes (optional)
author_notes:


date: '2026-04-25T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-04-25T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['conference']

# Publication metadata — structured fields used by citation styles and BibTeX export.
publication:
  name: "International Conference on Learning Representations (ICLR 2026)"
  short_name: "ICLR"

peer_reviewed: true
open_access: true
license: CC-BY-4.0

# Awards, honors, and recognitions. Surfaced as badges on the page and in listings.
awards:

# Funders and grants. Required by many funders for compliance reporting.
funding:
  - funder: "European Union’s Horizon Europe research and innovation"
    grant: "101120237 (ELIAS)"
  - funder: "Fondation de l’Ecole Polytechnique"
  - funder: "Hi! PARIS"
  - funder: "French National Research Agency"
    grant: "ANR-23-IACL-0005 and ANR-25-PEIA-0005"
  - funder: "NextGenerationEU"
  - funder: "MUR PNRR project PE0000013 CUP J53C22003010006 “Future Artificial Intelligence Research (FAIR)”"

abstract: The geometry of dynamical systems estimated from trajectory data is a major chal- lenge for machine learning applications. Koopman and transfer operators provide a linear representation of nonlinear dynamics through their spectral decomposition, offering a natural framework for comparison. We propose a novel approach that represents each system as a distribution over its joint operator eigenvalues and spectral projectors and defines a metric between systems leveraging optimal trans- port. The proposed metric is invariant to the sampling frequency of trajectories. It is also computationally efficient, supported by finite-sample convergence guarantees, and enables the computation of Fréchet means, providing interpolation between dynamical systems. Experiments on simulated and real-world datasets show that our approach consistently outperforms standard operator-based distances in machine learning applications, including dimensionality reduction and classification, and provides meaningful interpolation between dynamical systems.

# Summary. An optional shortened abstract.
summary: 

tags:
#  - Large Language Models

# Display this page in the Featured widget?
featured: True

# Standard identifiers for auto-linking
hugoblox:
#  ids:
#    doi: 10.5555/123456

# Custom links
links:
  - type: pdf
    url: "paper.pdf"
  - type: code
    url: https://github.com/thibaut-germain/SGOT
  - type: link
    url: https://proceedings.iclr.cc/paper_files/paper/2026/hash/c256585cb41de955198b9268cdc480d4-Abstract-Conference.html
#  - type: dataset
#    url: https://github.com/HugoBlox/kit
#  - type: slides
#    url: https://www.slideshare.net/
#  - type: source
#    url: https://github.com/HugoBlox/kit
#  - type: video
#    url: https://youtube.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/projects/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

> [!NOTE]
> Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the _Slides_ button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
