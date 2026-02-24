---
title: Diffusion models for Fast and accurate simulations of the low level CMS experiment data.
layout: gsoc_proposal
project: E2E
year: 2024
organization:
  - Alabama
  - NISER

---

## Description

One of the important aspects of searches for new physics at the Large Hadron Collider (LHC) involves the identification and reconstruction of single particles, jets and event topologies of interest in collision events. The End-to-End Deep Learning (E2E) project in the CMS experiment focuses on the development of these reconstruction and identification tasks with innovative deep learning approaches.

Diffusion based generative models are strong candidates for Fast Simulation models. The idea of this project is to build a diffusion-based ML model to model the underlying structure of the data which can be inturn be used for generating novel samples from the given distribution. Moreover this project also aims to explore conditional diffusion models that can generate specific types of data given a certain input to the model.
. 


## Duration

Total project length: 175/350 hours.

## Task ideas
 * Experiment with different Diffusion based models to find the best one suited for the E2E case.
 * Implementation of conditional diffusion models to generate samples based on specific given properties of the jets.



## Expected results
 * Implementation of a conditional diffusion model capable of generating realistic samples resembling the CMS E2E data.



## Difficulty level
Intermediate

## Requirements
Python, PyTorch and some previous experience in Machine Learning.

<!-- ## Test
Please use [this link](https://docs.google.com/document/d/1QuG0Ho3pWsJGMx0fG969aBNfgPg-cDxU9w33ZuDEBng/edit?usp=sharing) to access the test for this project. -->

## Mentors
  * [Emanuele Usai](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Sergei Gleyzer](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Diptarko Chaudhari](mailto:ml4-sci@cern.ch) (NISER)
  * [Eric Reinhardt](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Ruchi Chudasama](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Bhim Bam](mailto:ml4-sci@cern.ch) (University of Alabama)


Please **DO NOT** contact mentors directly by email. General questions can be directed to [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch). To submit your proposal, CV, and test task solutions, please use [this Google form](https://forms.gle/SPXo8kSwHHptcBmk9).

## Links
  * [Paper 1](https://arxiv.org/abs/2302.00236)
  * [Paper 2](https://arxiv.org/abs/2104.09459)

