---
title: Titans for Squared Amplitude Calculation
layout: gsoc_proposal
project: SYMBA
year: 2026
organization:
 - Alabama
---

## Description
One of the most important physical quantities in particle physics is the cross section, or a probability that a particular process takes place in the interaction of elementary particles. Its measure provides a testable link between theory and experiment. It is obtained theoretically mainly by calculating the squared amplitude. In this project we will explore Google’s recent Titans architecture combined with MIRAS to map from amplitudes to squared amplitudes using sequence to sequence representations.

## Duration
Total project length: 175/350 hours.

## Task ideas and expected results
  * Develop  symbolic models to predict squared amplitudes based on the Titans model architecture combined with MIRAS.
  * Quantify the performance of various Titans model frameworks using ablation studies.
  * Document results formally or informally to support ongoing research.

## Requirements 
Significant experience with developing models from literature in Python (preferably using pytorch).

## Difficulty Level 
Advanced

<!---
## Test
Please use this [link](https://docs.google.com/document/d/1zrBlte6vXNGTEFLFUGdXJm_B5mpSeWktif7mGtC4a-4/edit?usp=sharing) to access the test for this project.
--->

## Mentors
  * [Eric Reinhardt](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Sergei Gleyzer](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Marco Knipfer](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Victor Baules](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Dinesh Ramakrishnan](mailto:ml4-sci@cern.ch) (University of Alabama)

Please **DO NOT** contact mentors directly by email. Instead, please email [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch) with Project Title and **include your CV** and **test results**. The mentors will then get in touch with you.

## Links
  * [Paper 1](https://arxiv.org/html/2501.00663v1)
  * [Paper 2](https://arxiv.org/abs/2312.00752)
  * [Paper 3](https://iopscience.iop.org/article/10.1088/2632-2153/acb2b2)
  * [Paper 4](https://research.google/blog/titans-miras-helping-ai-have-long-term-memory/)