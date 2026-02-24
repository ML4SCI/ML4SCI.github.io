---
title: Data Augmentation Using Physics-Informed Plaque Growth Simulation
layout: gsoc_proposal
project: PREDICT
year: 2026
organization:
 - Alabama
 - Kettering
---

## Description
A key challenge in medical image segmentation and feature analysis is data availability due to IRB and regulatory hurdles. The recent interest in applying ML to medical image analysis demands large and diverse datasets, making data augmentation strategies critical for medical imaging.
Project PrediCT aims to leverage data augmentation to boost segmentation and prediction pipelines. However, synthetic calcium plaque data is difficult to produce given the specific nature of calcium deposition patterns and required anatomical accuracy. This project will develop a physics-informed simulation framework to generate synthetic calcium masks for CAC scoring scans.
Our approach is to use atlas-based vessel territories combined with hemodynamic-inspired placement rules (rather than exact centerlines) to generate anatomically plausible synthetic calcium. Contributors can optionally incorporate diffusion models for lesion morphology while using rule-based placement to ensure physical constraints.

## Duration
Total project length: 175/350 hours.

## Difficulty Level
  * Advanced

## Task ideas
  * Register CAC scans to publicly available coronary anatomy atlas to obtain approximate LAD/LCX/RCA vessel territories 
  * Create hemodynamic-inspired probability maps for calcium placement 
  * Extract real calcium lesion morphologies from COCA dataset, cluster into templates (spotty/dense/diffuse types), potentially collaborating with another contributor here
  * Implement rule-based placement algorithm (i.e. sample number of lesions from Agatston target, place according to probability maps, assign morphologies from library)
  * Optionally use diffusion model to generate lesion morphology variations while maintaining physics-based spatial placement 
  * Create procedural generation pipeline accepting parameters (desired Agatston score, phenotype, vessel distribution) 
  * Validate synthetic scans via statistical distribution matching (KS test, chi-square), expert Turing test with board-certified cardiologist (target: <60% distinguishability), morphological feature comparison
  
 
## Expected results
  * Synthetic calcium generation pipeline capable of producing scans with controllable Agatston scores and phenotypes 
  * Statistical validation report: synthetic vs. real comparison on Agatston distribution, lesion count, spatial patterns, vessel territory distribution
  * Expert validation: Turing test results with cardiologist review of realism 
  * Downstream validation: nnU-Net segmentation improvement when trained on real + synthetic vs. real-only data 
  * Anatomical plausibility checks: >95% of synthetic calcium within expected coronary territories 
  
 
## Test 
Please use [this link](https://bama365-my.sharepoint.com/:w:/g/personal/kebutler2_crimson_ua_edu/IQDKCgBG6yGTR6c6sdaWWjdoAcp1SPRuuSdtVg3UEKB-vWE?e=4rPSFu) to access the test for this project.
  
## Requirements 
  *	Proficiency in Python
  *	Understanding basic medical imaging processing, cardiac CT, and image registration, or willingness to learn
  *	Strong interest in learning cardiovascular anatomy, calcium pathophysiology, and hemodynamics
  
  

## Mentors
  * [Kathleen Butler](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Anna Marie Love](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Sergei Gleyzer](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Harvey Hahn](mailto:ml4-sci@cern.ch) (Kettering Health Network)

## Links
  * [Paper 1](https://link.springer.com/article/10.1007/s10462-025-11303-w#Sec19)
  * [Coronary Atlas](https://www.coronaryatlas.org/)
  * [Paper 2](https://arxiv.org/abs/2403.00177)
  * [Paper 3](https://ieeexplore.ieee.org/document/4738331)
  * [Paper 4](https://eurointervention.pcronline.com/article/impact-of-local-flow-haemodynamics-on-atherosclerosis-in-coronary-artery-bifurcations?utm_source=chatgpt.com)
  * [Paper 5](https://www.mdpi.com/2075-4418/10/2/91?utm_source=chatgpt.com)

Please **DO NOT** contact mentors directly by email. General questions can be directed to [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch). To submit your solutions, please use [this Google form](https://forms.gle/SPXo8kSwHHptcBmk9).


