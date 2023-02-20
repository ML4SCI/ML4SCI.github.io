---
title: End-to-End Deep Learning Reconstruction for CMS Experiment
layout: gsoc_proposal
project: CMS
year: 2021
organization:
  - Alabama
  - New York University
  - Brown
  - Vishwakarma Institute of Technology

---

## Description

One of the important aspects of searches for new physics at the [Large Hadron Collider (LHC)](https://home.cern/science/accelerators/large-hadron-collider) involves the identification and reconstruction of single particles, jets and event topologies of interest in collision events. The End-to-End Deep Learning (E2E) project in the CMS experiment focuses on the development  of these reconstruction and identification tasks with innovative deep learning approaches.   

This project will focus on the integration of E2E code with the [CMSSW](https://github.com/cms-sw/cmssw) inference engine for use in reconstruction algorithms in offline and high-level trigger systems of the [CMS](https://home.cern/science/experiments/cms) experiment.



## Task ideas
 * Include Sonic support to the inference. Bring the cpu execution part to GPUs in the inference ([Reference](https://github.com/andyburton/Sonic-CMS))
 * Add support for Vision transformers
 * Add pytorch support to the inference ([Reference](https://cms-ml.github.io/documentation/inference/pytorch.html))

## Expected results
 * Integrated code within CMSSW classes
 * Benchmark of end-to-end deep learning inference on cpu and gpu


## Requirements
C++, Python, PyTorch and some previous experience in Machine Learning.

## Task
Please use this link to access the test for this project. Tests will be published by Feb. 24

## Mentors
  * [Emanuele Usai](mailto:ml4-sci@cern.ch) (Brown University)
  * [Ruchi Chudasama](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Shravan Chaudhari](mailto:ml4-sci@cern.ch) (BITS Pilani Goa)
  * [Sergei Gleyzer](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Purva Chaudhari](mailto:ml4-sci@cern.ch) (Vishwakarma Institute of Technology)


Please DO NOT contact mentors directly by email, and instead please send project inquiries to [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch) with Project Title in the subject and relevant mentors will get in touch with you. 



## Links
  * [Paper 1](https://arxiv.org/abs/1807.11916)
  * [Paper 2](https://arxiv.org/abs/1902.08276)