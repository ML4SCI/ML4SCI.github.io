---
title: Using Next-Gen Transformers to Seed Generative Models for Symbolic Regression
layout: gsoc_proposal
project: SYMBA
year: 2026
organization:
 - Alabama
---

## Description
Symbolic regression can be used to rapidly provide solutions to problems in science which may have large computational complexity or may even be intractable. It can be used to discover a symbolic expression describing data such as a physical law. Previous work has explored next-generation transformers[2][6] based on SymbolicGPT[3] for symbolic regression and, separately, using transformers to seed generative techniques such as genetic programming and reinforcement learning[1][4][5]. This project aims to combine recent developments in transformer models with generative frameworks. Projects which build upon previous projects will be given priority.

## Duration
Total project length: 175/350 hours.

## Task ideas and expected results
  * Implement a solution combining modern transformer models with generative techniques.
  * Quantify the benefit provided by combining various techniques using ablation studies.
  * Document results formally or informally to support ongoing research.
   
## Requirements 
Significant experience with Transformer machine learning models in Python (preferably using pytorch). Experience with reinforcement learning, genetic programming, or other generative frameworks is preferred.

## Difficulty Level 
Intermediate

## Test
Please use this [link](https://docs.google.com/document/d/1rQlU-iwm3-t7Bs75n1Dl-AvifUL36K60JVjM6Wi2W8E/edit?usp=sharing) to access the test for this project.


## Mentors
  * [Eric Reinhardt](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Dinesh Ramakrishnan](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Sergei Gleyzer](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Nobuchika Okada](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Ritesh Bhalerao](mailto:ml4-sci@cern.ch)

Please **DO NOT** contact mentors directly by email. General questions can be directed to [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch). To submit your proposal, CV, and test task solutions, please use [this Google form](https://forms.gle/SPXo8kSwHHptcBmk9).

## Links
  * \[1\][Paper 1](https://ml4physicalsciences.github.io/2024/files/NeurIPS_ML4PS_2024_115.pdf)
  * \[2\][Paper 2](https://ml4physicalsciences.github.io/2025/files/NeurIPS_ML4PS_2025_285.pdf)
  * \[3\][Paper 3](https://arxiv.org/pdf/2106.14131)
  * \[4\][Blog Post 1](https://medium.com/@aryamaanthakur/transformers-meet-evolution-a-hybrid-approach-to-symbolic-regression-final-progress-gsoc-0de041ac013d)
  * \[5\][Blog Post 2](https://medium.com/@samyakjha71/symbolic-regression-gsoc-24-final-evaluations-40aea5aad6dd)
  * \[6\][Blog Post 3](https://medium.com/@krishmalikus/learning-symbolic-expressions-from-data-clouds-d186f05435bd)
  * [Code](https://github.com/ML4SCI/SYMBA/tree/main/SYMBA_REG)