---
title: "Pattern detection and shape analysis for physiological timeseries"
authors:
  - "me"
date: "2024-01-01T00:00:00Z"
publishDate: "2024-01-01T00:00:00Z"
publication_types: ["thesis"]
publication:
  name: "Université Paris-Saclay"
  short_name: "PhD thesis"
peer_reviewed: false
open_access: true
abstract: >-
  Time series are prevalent in biomedical applications where they frequently display recurring or abnormal patterns that hold significant information for statistical analysis. A notable example is the heartbeat in electrocardiograms, a recurring pattern whose shape can vary depending on the underlying condition, making it an important feature for diagnosing heart-related diseases. However, comparing such patterns requires specialized mathematical tools lying at the intersection between machine learning for time series and shape analysis. 
  

  While the shape analysis community has partially addressed the case of time series, shape related approaches from machine learning for time series have achieved great success in various applications. This thesis aims to combine the strengths of both fields to propose methods suitable for biomedical research depending on temporal data. Particular attention will be given to methods’ interpretability through visual interpretation of patterns and deformations, as it is key for meaningful interaction between the data and biomedical researchers.
  

  The thesis is structured into two parts: the first focuses on searching for and discovering valuable patterns in time series, while the second concentrates on pattern comparison. 

  
  The first part tackles the challenge of searching or discovering patterns in long time series with distances independent of some irrelevant sources of variability modeled with a group of deformations. To that end, a general framework for constructing deformation-invariant distances is introduced. This framework extends the well-known Z-normalized Euclidean distance, invariant to amplitude scaling and offset shifts, by allowing customization of the group of deformations. The custom distances can be integrated into state-of-the-art algorithms for similarity search and motif discovery without efficiency loss. Additionally, an interpretable and interactive algorithm for motif discovery has been developed. This algorithm maps a time series onto a graph which is then summarized into a diagram providing a visual interpretation that facilitates the identification of recurring patterns. Furthermore, an interactive application has been designed for biomedical researchers, leveraging the algorithm’s interpretability and efficiency for effective motif discovery. 
  
 
  The second part focuses on comparing temporal patterns using elastic deformations that notably account for time warping. The proposed methods are driven by the analysis of mice respiratory cycles recorded via plethysmography to identify ventilation modalities and assess the respiratory changes in mice with different genotypes after exposure to a drug affecting respiration. The first method compares respiratory cycles with a clustering algorithm based on the Dynamic Time Warping distance. Designed as a baseline, experimental results show that clusters have physiological relevance, reflecting genotype-specific ventilation modalities and responses to drug exposure. The second method creates fixed-size vector representations of irregularly sampled and variable-length time series by the vector parametrizing the deformations that map a reference time series to the observed ones. This approach draws on the Large Deformation Diffeomorphic Metric Mapping (LDDMM) framework from shape analysis, which is refined to maintain the spatiotemporal structure of the deformed time series while ensuring the bijectivity of the embedding. This method provides both statistical insights and visual interpretations of shapes and deformations. A simple statistical analysis reveals that the deformations responsible for most variability carry physiological significance, offering insights into ventilation modalities with respect to genotype and drug exposure effects. 
summary:
featured: false
tags: []
hugoblox:
  ids: {}
links:
  - type: pdf
    url: "paper.pdf"
  - type: link
    url: "https://theses.hal.science/tel-04880442/"
projects: []
slides: ""
---
