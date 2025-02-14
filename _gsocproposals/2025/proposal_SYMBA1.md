---
title: Next-Gen Transformer Models for Symbolic Calculations of Squared Amplitudes in HEP
layout: gsoc_proposal
project: SYMBA
year: 2025
organization:
 - Alabama
 - FSU
 - QU

---

## Description

One of the most important physical quantities in particle physics is the cross section, or a probability that a particular process takes place in the interaction of elementary particles. Its measure provides a testable link between theory and experiment. It is obtained theoretically mainly by calculating the squared amplitude. The approach we use in this project is to treat the amplitude and squared amplitude as mathematical symbolic expressions and use language-translation models to map from the amplitude to squared-amplitude. This project will explore uses of more advanced techniques which could include but are not limited to Kolmogorov-Arnold Network layers in transformers, genetic algorithms and other evolutionary techniques, reinforcement learning.

## Duration

Total project length: 175/350 hours.

## Task ideas and expected results
  * Develop  various transformer-based models on sequence-to-sequence tasks
  * Benchmark different models on simulated physics datasets of various complexity and sequence lengths to find the best model
  * Integrate with the SymbaHEP pipeline
   
## Requirements 
Significant experience with Transformer machine learning models in Python (preferably using pytorch).

## Difficulty Level 
Advanced

<!-- ## Test
Please use this [link](https://docs.google.com/document/d/19ybdCLbxJs2mFsxni4yN9FP4ADlK4mxltF9OVSmbRXE/edit?usp=sharing) to access the test for this project. -->

## Mentors
  * [Eric Reinhardt](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Abdulhakim Alnuqaydan](mailto:ml4-sci@cern.ch) (Qassim University)
  * [Sergei Gleyzer](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Harrison Prosper](mailto:ml4-sci@cern.ch) (Florida State University)
  * [Nobuchika Okada](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Marco Knipfer](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Victor Baules](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Dinesh Ramakrishnan](mailto:ml4-sci@cern.ch) (University of Alabama)

Please **DO NOT** contact mentors directly by email. Instead, please email [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch) with Project Title and **include your CV** and **test results**. The mentors will then get in touch with you.

## Links
  * [Paper 1](https://ml4physicalsciences.github.io/2023/files/NeurIPS_ML4PS_2023_183.pdf)
  * [Paper 2](https://iopscience.iop.org/article/10.1088/2632-2153/acb2b2)
  * [Poster 1](https://nips.cc/media/PosterPDFs/NeurIPS%202023/76219.png)
  * [Blog post 1](https://medium.com/@neerajanandfirst/my-journey-to-google-summer-of-code-2023-with-ml4sci-8822ce64464a)
