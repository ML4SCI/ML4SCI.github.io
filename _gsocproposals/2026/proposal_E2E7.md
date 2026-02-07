---
title: Foundation models for End-to-End event reconstruction
layout: gsoc_proposal
project: E2E
year: 2026
organization:
  - Alabama
  - NISER
  - New York University
  - Vishwakarma Institute of Technology
---


## Description
One of the important aspects of searches for new physics at the [Large Hadron Collider (LHC)](https://home.cern/science/accelerators/large-hadron-collider) involves the identification and reconstruction of single particles, jets and event topologies of interest in collision events. The End-to-End Deep Learning (E2E) project in the CMS experiment focuses on the development  of these reconstruction and identification tasks with innovative deep learning approaches.   


This project will focus on the development of foundation models for end-to-end particle reconstruction with the goal of performing generative, classification and regression tasks. Proposals can build on last year's work which combined the L-GATr and ParT models and implemented a track-level masked autoencoder pretraining and present strategies to meaningfully improve on these techniques. This project is related to the project Event Classification With Masked Transformer Autoencoders but should focus primarily on developing complete multi-modal foundation model training pipelines.

## Duration
Total project length: 175/350 hours

## Difficulty level
Advanced

## Task ideas
 * Develop a pre-training strategy for learning robust representations of high-energy physics detector data
*  Fine-tune the foundation model for multiple tasks such as classification, generative, super-resolution, and regression
* Evaluate the model’s performance on different HEP datasets and benchmark against individual methods for classification, regression etc

## Expected results
 * Trained foundation model and benchmarks 
## Requirements
C++, Python, PyTorch and some previous experience in Machine Learning.

<!---
## Test
Please use [this link](https://docs.google.com/document/d/10tITU-OJDtaZkLmXpoCpzIM55XcV4Z_7ykS7N9tyISA/edit?usp=sharing) to access the test for this project.
--->

## Mentors
  * [Ruchi Chudasama](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Shravan Chaudhari](mailto:ml4-sci@cern.ch) (New York University)
  * [Sergei Gleyzer](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Purva Chaudhari](mailto:ml4-sci@cern.ch) (Vishwakarma Institute of Technology)
  * [Diptarko Choudhury](mailto:ml4-sci@cern.ch) (NISER)


Please **DO NOT** contact mentors directly by email. Instead, please email [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch) with Project Title and **include your CV** and **test results**. The mentors will then get in touch with you.

## Links
  * [Blog Post 1](https://medium.com/@thanhnguyen14401/gsoc-2025-with-ml4sci-event-classification-with-masked-transformer-autoencoders-6da369d42140)
  * [Paper 1](https://arxiv.org/abs/2405.14806)
  * [Paper 2](https://arxiv.org/abs/2202.03772)
  * [Code](https://github.com/ML4SCI/CMS/tree/main/MAEs/Hybrid_Transformer_Thanh_Nguyen)