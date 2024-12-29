---
title: Masked Auto-Encoders for Efficient End-to-End Particle Reconstruction and Compression for the CMS Experiment
layout: gsoc_proposal
project: E2E
year: 2024
organization:
  - Alabama
  - NISER
  - New York University

---

## Description

One of the important aspects of searches for new physics at the [Large Hadron Collider (LHC)](https://home.cern/science/accelerators/large-hadron-collider) involves the identification and reconstruction of single particles, jets and event topologies of interest in collision events. The End-to-End Deep Learning (E2E) project in the CMS experiment focuses on the development  of these reconstruction and identification tasks with innovative deep learning approaches.

The data involved in these tasks are often sparse low-level detector information, which is computationally expensive to store and process. Recent works have shown masked auto-encoders to be a viable alternative to generic autoencoder-based architecture for data compression and downstream transfer learning-based tasks. The aim of this project will be to develop state-of-the-art Vision-Tranformer-based hybrid masked autoencoders to achieve competitive reconstruction and transfer learning scores when compared to pre-existing methods.

## Duration

Total project length: 175/350 hours.

## Task ideas
 * Develop MAE (Masked Auto Encoders) with Vision-Transformer based encoders to compress the sparse images to feature vectors.
 * Test Reconstruction Error and Downstream Task (classification and regression) score and compare it to existing baselines.
 * Extend the idea of MAE to hybrid (Conv + ViT) architectures and compare score for downstream tasks.



## Expected results
 * Development of state-of-the-art encoder based on hybrid ViT architectures trained using Masked Auto-Encoder Loss to compress E2E data to feature vectors.


## Difficulty level
Advanced

## Requirements
C++, Python, PyTorch, Tensorflow and some previous experience in Deep Learning.

<!-- ## Test
Please use [this link](https://docs.google.com/document/d/1QuG0Ho3pWsJGMx0fG969aBNfgPg-cDxU9w33ZuDEBng/edit?usp=sharing) to access the test for this project. -->

## Mentors
  * [Emanuele Usai](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Diptarko Choudhury](mailto:ml4-sci@cern.ch) (NISER)
  * [Sergei Gleyzer](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Ruchi Chudasama](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Shravan Chaudhari](mailto:ml4-sci@cern.ch) (New York University)
  * [Bhim Bam](mailto:ml4-sci@cern.ch) (University of Alabama)



Please **DO NOT** contact mentors directly by email. Instead, please email [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch) with Project Title and **include your CV** and **test results**. The mentors will then get in touch with you.

## Links
  * [Paper 1](https://arxiv.org/abs/2111.06377)
