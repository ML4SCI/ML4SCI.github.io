---
title: Building and Comparing Segmentation Strategies for Coronary Artery Calcium (CAC)
layout: gsoc_proposal
project: PREDICT
year: 2026
organization:
 - Alabama
 - Kettering
---

## Description
Accurate segmentation of coronary artery calcium (CAC) in non-contrast cardiac CT is a key step toward automated quantitative scoring and downstream clinical prediction (e.g., MACE risk). CAC segmentation is challenging due to small, scattered high-intensity lesions; severe class imbalance; frequent false positives from osseous structures (e.g., ribs, vertebrae); and imaging noise and partial volume effects.
This project will implement and systematically compare multiple machine learning segmentation strategies on the Stanford COCA dataset, with the goal of balancing segmentation accuracy, architectural efficiency, and long-range contextual modeling. Results will establish reproducible pipelines for preprocessing, model training, evaluation, and CAC burden quantification suitable for future work on unlabeled datasets and clinical modeling

## Duration
Total project length: 175/350 hours.

## Difficulty Level
  * Advanced

## Task ideas
  *	Create preprocessing pipeline, with intensity normalization and strategic data augmentation. 
  *	Build and train segmentation models such as 2.5D U-Net variants, hybrid CNN-transformers, and domain-adaptation/self-supervised models and compare against nnU-Net (strong, established model)
  *	Anatomical localization head assigning segmented plaques to specific coronary arteries, where labels permit
  *	Implement an Agatston scoring script using both ground-truth and model segmentations to assess clinical relevance of segmentation quality.
 
## Expected results
  * Multiple trained segmentation models with documented performance.
  * Fair, reproducible comparisons using standard metrics (e.g., Dice coefficient, precision/recall, AUC).
  * Quantitative comparison of Agatston scores computed from model vs. annotated segmentations.
  * Demonstration of CAC anatomical attribution
 
## Test 
Please use [this link](https://bama365-my.sharepoint.com/:w:/g/personal/kebutler2_crimson_ua_edu/IQDKCgBG6yGTR6c6sdaWWjdoAcp1SPRuuSdtVg3UEKB-vWE?e=4rPSFu) to access the test for this project.
  
## Requirements 
  * Experience in Python and PyTorch (or equivalent deep learning framework).
  * Practical experience with CNNs and segmentation (e.g., U-Net, attention mechanisms).
  * Familiarity with medical imaging data formats and coronary artery anatomy or willingness to learn quickly
  * Understanding of evaluation metrics for segmentation and clinical scoring or willingness to learn quickly

## Mentors
  * [Kathleen Butler](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Anna Marie Love](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Sergei Gleyzer](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Harvey Hahn](mailto:ml4-sci@cern.ch) (Kettering Health Network)

## Links
  * [Paper 1](https://arxiv.org/abs/1505.04597)
  * [Paper 2](https://www.sciencedirect.com/science/article/pii/S136184152500369X)
  * [Paper 3](https://arxiv.org/abs/2109.03201)
  * [Paper 4](https://arxiv.org/abs/1612.08894)
  * [Paper 5](https://www.sciencedirect.com/science/article/pii/S2950162825000025)
  * [Code](https://github.com/MIC-DKFZ/nnUNet) 

Please **DO NOT** contact mentors directly by email. General questions can be directed to [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch). To submit your proposal, CV, and test task solutions, please use [this Google form](https://forms.gle/SPXo8kSwHHptcBmk9).


