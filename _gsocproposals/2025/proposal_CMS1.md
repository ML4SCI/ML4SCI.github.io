---
title: Event Classification With Masked Transformer Autoencoders
layout: gsoc_proposal
project: CMS
year: 2025
organization:
  - Alabama
  - NISER
---

## Description

One of the key tasks in particle physics analyses is proper classification of particle collision events based on the parent particles and the process that produced them. To handle this task, we’re developing a flexible machine learning pipeline which can be applied to a broad range of classification tasks. We’ll leverage a mix of older and newer techniques for transformer models like masking, pretraining using autoencoder architectures, and cross attention of task-specific attention heads.

## Duration

Total project length: 175/350 hours.

## Task ideas
 * Develop a scalable transformer encoder model with task-specific attention heads combined using a cross attention mechanism
 * Improve existing code pipeline with features like multi-GPU parallelism and flexible preprocessing and analysis options
 * Deploy the developed models and pipeline on simulated physics data and analyze performance gains and changes in model understanding from the techniques used

## Test
Please use [this link](https://docs.google.com/document/d/10tITU-OJDtaZkLmXpoCpzIM55XcV4Z_7ykS7N9tyISA/edit?usp=sharing) to access the test for this project.

## Requirements
Significant experience in Python and Machine Learning in Pytorch. Preferably some experience with Transformers and multi-GPU parallelization or with the ROOT library developed by CERN. 

## Difficulty Level
Advanced

## Mentors
  * [Eric Reinhardt](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Diptarko Choudhury](mailto:ml4-sci@cern.ch) (NISER)
  * [Ruchi Chudasama](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Emanuele Usai](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Sergei Gleyzer ](mailto:ml4-sci@cern.ch) (University of Alabama)


Please **DO NOT** contact mentors directly by email. Instead, please email [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch) with Project Title and **include your CV** and **test results**. The mentors will then get in touch with you.


## Links
  * [Blog Post 1](https://medium.com/@eric0reinhardt/gsoc-2023-with-ml4sci-reconstruction-and-classification-of-particle-collisions-with-masked-bab8b38958df)
  * [Paper 1](https://arxiv.org/abs/2401.00452)
