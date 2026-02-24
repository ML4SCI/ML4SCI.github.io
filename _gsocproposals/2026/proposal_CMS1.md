---
title: Event Classification With Masked Transformer Autoencoders
layout: gsoc_proposal
project: CMS
year: 2026
organization:
  - Alabama
  - NISER
---

## Description

One of the key tasks in particle physics analyses is proper classification of particle collision events based on the parent particles and the process that produced them. To handle this task, we're developing a flexible machine learning pipeline which can be applied to a broad range of classification tasks. Proposals should build on last year's work which combined the L-GATr and ParT models and implemented a track-level masked autoencoder pretraining. This project is related to the project "Foundation models for End-to-End event reconstruction" but should focus primarily on improving the existing hybrid model architectures either in speed or numerical accuracy and quantifying results.

## Duration

Total project length: 175/350 hours.

## Task ideas
 * Improve existing code pipeline with techniques such as attention gating, JEPA, or other well-motivated ideas
 * Implement optimization strategies and/or custom GPU kernels to accelerate L-GATr layers
 * Carry out extensive ablation studies to quantify performance gains from autoencoder pretraining and model hybridization
 * Extend work to also include particle mass regression
 * Document results formally or informally to support ongoing research.

## Test
Please use [this link](https://docs.google.com/document/d/12oC-SEoWlBq-9MYNKAUMHopnB4tvQcRhbjY0MOW0jiY/edit?usp=sharing) to access the test for this project.

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


Please **DO NOT** contact mentors directly by email. General questions can be directed to [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch). To submit your solutions, please use [this Google form](https://forms.gle/SPXo8kSwHHptcBmk9).


## Links
  * [Blog Post 1](https://medium.com/@thanhnguyen14401/gsoc-2025-with-ml4sci-event-classification-with-masked-transformer-autoencoders-6da369d42140)
  * [Paper 1](https://arxiv.org/abs/2405.14806)
  * [Paper 2](https://arxiv.org/abs/2202.03772)
  * [Code](https://github.com/ML4SCI/CMS/tree/main/MAEs/Hybrid_Transformer_Thanh_Nguyen)
