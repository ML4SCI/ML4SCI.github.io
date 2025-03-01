---
title: End-to-End event classification with sparse autoencoders
layout: gsoc_proposal
project: E2E
year: 2025
organization:
  - Alabama
  - NISER

---

## Description

One of the key tasks in particle physics analyses is proper classification of particle collision events based on the parent particles and the process that produced them. To handle this task, we’re developing a flexible machine learning pipeline which can be applied to a broad range of classification tasks. This project will primarily explore the development of sparse autoencoders which can effectively handle particle collision information represented as minimally processed images where the majority of the pixels in the image have very low or zero value. Different techniques have been developed to handle sparse representations such as sparse convolutions and point-cloud structures.



## Duration

Total project length: 175/350 hours.

## Task ideas
* Develop a scalable sparse autoencoder model pipeline for event classification and reconstruction.

## Expected results
* Improve existing code pipeline with features like multi-GPU parallelism and flexible preprocessing and analysis options.
* Deploy the developed models and pipeline on simulated physics data and analyze performance gains and changes in model understanding from the techniques used.


## Difficulty level
Advanced

## Requirements
* Significant experience in Python and Machine Learning in Pytorch. 
* Preferably some experience with Transformers and multi-GPU parallelization or with the ROOT library developed by CERN.

## Test
Please use [this link](https://docs.google.com/document/d/10tITU-OJDtaZkLmXpoCpzIM55XcV4Z_7ykS7N9tyISA/edit?usp=sharing) to access the test for this project.

## Mentors
  * [Diptarko Choudhury](mailto:ml4-sci@cern.ch) (NISER)
  * [Sergei Gleyzer](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Ruchi Chudasama](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Eric Reinhardt](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Emanuele Usai](mailto:ml4-sci@cern.ch) (University of Alabama)


Please **DO NOT** contact mentors directly by email. Instead, please email [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch) with Project Title and **include your CV** and **test results**. The mentors will then get in touch with you.

## Links
  * [Paper 1](https://arxiv.org/pdf/1706.01307)
  * [Paper 2](https://arxiv.org/abs/1712.07262)
  * [Paper 3](https://arxiv.org/pdf/1902.08276)
