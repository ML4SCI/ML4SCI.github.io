---
title: Super resolution at the CMS detector
layout: gsoc_proposal
project: E2E
year: 2026
organization:
  - Alabama

---

## Description

One of the important aspects of searches for new physics at the Large Hadron Collider (LHC) involves the identification and reconstruction of single particles, jets and event topologies of interest in collision events. In order to correctly reconstruct particles of interest, high resolution is required.

This project will focus on developing machine learning models to map processed, lower resolution data from particle from simulated particle collisions back to a higher resolution representation. This project should specifically explore modern techniques leveraging transformer neural networks such as Visual Autoregression, Joint Embedding Predictive Architectures, and/or Diffusion. This project is crosslisted with E2E and CMS.

## Duration

Total project length: 175/350 hours.

## Task ideas
 * Develop a machine-learning super-resolution model to upsample particle collision data
 * Analyze performance on ground-truth simulated higher resolution data
 
## Expected results
 *  Trained models and benchmarks on simulated data

<!---
## Test
Please use [this link](https://docs.google.com/document/d/10tITU-OJDtaZkLmXpoCpzIM55XcV4Z_7ykS7N9tyISA/edit?usp=sharing) to access the test for this project.
--->

## Requirements
Python, C++, and some previous experience in Machine Learning. 

## Mentors


Please **DO NOT** contact mentors directly by email. Instead, please email [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch) with Project Title and **include your CV** and **test results**. The mentors will then get in touch with you.


## Links
  * [Paper 1](https://arxiv.org/pdf/2409.16052)
  * [Paper 2](https://ml4physicalsciences.github.io/2024/files/NeurIPS_ML4PS_2024_89.pdf)
  * [Paper 3](https://arxiv.org/abs/2404.02905)
  * [Paper 4](https://arxiv.org/abs/2506.09985)
