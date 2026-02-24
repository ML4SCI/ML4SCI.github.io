---
title: Radiomics Feature Extraction and Calcium Phenotype Discovery
layout: gsoc_proposal
project: PREDICT
year: 2026
organization:
 - Alabama
 - Kettering
---

## Description
Coronary artery calcium (CAC) scoring traditionally uses the Agatston score, a single number representing calcium burden, as robust major adverse cardiac event (MACE) predictor. However, recent research shows that calcium morphology patterns provide additional predictive value for MACE beyond total calcium burden alone.
PrediCT is working with the Stanford COCA dataset (gated CAC scans with segmentation masks) but currently lacks MACE endpoints. This project will develop a feature extraction and phenotyping framework that extracts radiomics features (shape, texture, spatial distribution) from calcium masks, applies dimensionality reduction to identify key features, and discovers calcium phenotypes via unsupervised clustering.
We aim to develop a validation framework for discovered phenotypes without clinical endpoints, a novel approach. This can be done through Agatston correlation, reproducibility testing, and clinical pattern alignment.

## Duration
Total project length: 175/350 hours.

## Difficulty Level
  * Intermediate

## Task ideas
  Contributors have creative freedom to explore calcium features. Suggested approaches:
  * Extract shape features (volume, sphericity, elongation, surface-to-volume ratio), intensity features (mean/max HU, histograms), texture features (GLCM: contrast, entropy), and spatial features (lesion count, inter-lesion distances) using PyRadiomics and SimpleITK
  * Apply dimensionality reduction via PCA to create "eigen features" (inspired by Paper 1)
  * Perform unsupervised clustering (K-means, hierarchical, DBSCAN, GMM) to discover calcium phenotypes
  * Visualize feature space with t-SNE/UMAP, analyze phenotype correlation with Agatston score
  * Test feature invariance: apply perturbations (rotation ±5°, translation, noise) and measure phenotype consistency
  * Group scans into literature-derived patterns (spotty/dense/diffuse) and validate against discovered phenotypes
  * Analyze vessel territory distribution: do phenotypes correlate with anatomical location?
 
## Expected results
  * A robust and documented feature extraction pipeline for 50-100 features from all gated COCA scans
  * Extract and validate distinct calcium phenotypes via clustering with clear characteristics
  * Validate features and phenotypes via Agatston stratification, cluster quality, reproducibility post image perturbation, and clinical alignment with known calcium patterns
  * Identify which features are the main phenotype distinguishers via random forest, SHAP, etc.
 
## Test 
Please use [this link](https://bama365-my.sharepoint.com/:w:/g/personal/kebutler2_crimson_ua_edu/IQDKCgBG6yGTR6c6sdaWWjdoAcp1SPRuuSdtVg3UEKB-vWE?e=4rPSFu) to access the test for this project.
  
## Requirements 
  * Proficiency in Python, ML (clustering, PCA, validation metrics), and data visualization skills
  *	Understanding basic medical imaging processing and cardiac CT, or strong willingness to learn
  

## Mentors
  * [Kathleen Butler](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Anna Marie Love](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Sergei Gleyzer](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Harvey Hahn](mailto:ml4-sci@cern.ch) (Kettering Health Network)

## Links
  * [Paper 1](https://www.sciencedirect.com/science/article/abs/pii/S1936878X24003760?via%3Dihub#preview-section-snippets)
  * [Paper 2](https://www.semanticscholar.org/paper/3D-CT-Based-Coronary-Calcium-Assessment%3A-A-Machine-Abaid-Guidone/314e5c78a807e953c87942eeb6ef8b74e1508836)
  * [Paper 3](https://www.nature.com/articles/s41598-024-60584-8)
  * [Paper 4](https://www.sciencedirect.com/science/article/pii/S1936878X21008469)
  * [Code](https://pyradiomics.readthedocs.io/en/latest/)

Please **DO NOT** contact mentors directly by email. General questions can be directed to [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch). To submit your solutions, please use [this Google form](https://forms.gle/SPXo8kSwHHptcBmk9).


