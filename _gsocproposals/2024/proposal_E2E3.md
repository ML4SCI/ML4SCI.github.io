---
title: Self-Supervised Learning for End-to-End Particle Reconstruction for the CMS Experiment
layout: gsoc_proposal
project: E2E
year: 2024
organization:
  - Alabama
  - NISER

---

## Description

One of the important aspects of searches for new physics at the [Large Hadron Collider (LHC)](https://home.cern/science/accelerators/large-hadron-collider) involves the identification and reconstruction of single particles, jets and event topologies of interest in collision events. The End-to-End Deep Learning (E2E) project in the CMS experiment focuses on the development  of these reconstruction and identification tasks with innovative deep learning approaches.

Transfer learning and Self-Supervised learning techniques often outperform traditional models that are trained from scratch. State-of-the-art SSL (Self-Supervised Learning) techniques, when applied to unlabelled data, learn useful features without annotation. Later, when these models are finetuned with the limited labelled data, a higher level of generality is observed. This project explores Self-Supervised Contrastive/Clustering/Distillation based Learning techniques to build robust models that perform better than the existing supervised baselines.

## Duration

Total project length: 175/350 hours.

## Task ideas
 * Explore Contrastive/Clustering/Distillation based techniques to train an encoder with rich feature vectors,
 * Extend the study by fine-tuning with labelled data and comparing the results with pre-existing supervised baselines.
 * Extend the idea of SSL to hybrid (Conv + ViT) architectures and compare scores for downstream tasks.



## Expected results
 * Development of a robust SSL-based pipeline that can be used to train neural networks which can be later fine-tuned to produce state-of-the-art results for downstream tasks.


## Difficulty level
Advanced

## Requirements
C++, Python, PyTorch, Tensorflow and some previous experience in Deep Learning.

## Test
Please use [this link](https://docs.google.com/document/d/1QuG0Ho3pWsJGMx0fG969aBNfgPg-cDxU9w33ZuDEBng/edit?usp=sharing) to access the test for this project.

## Mentors
  * [Emanuele Usai](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Diptarko Choudhury](mailto:ml4-sci@cern.ch) (NISER)
  * [Sergei Gleyzer](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Ruchi Chudasama](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Eric Reinhardt](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Colin Crovella](mailto:ml4-sci@cern.ch) (University of Alabama)



Please **DO NOT** contact mentors directly by email. Instead, please email [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch) with Project Title and **include your CV** and **test results**. The mentors will then get in touch with you.

## Links
  * [Paper 1](https://arxiv.org/abs/2105.04906)
  * [Paper 2](https://arxiv.org/abs/2006.07733)
  * [Paper 3](https://arxiv.org/abs/2006.10029)
