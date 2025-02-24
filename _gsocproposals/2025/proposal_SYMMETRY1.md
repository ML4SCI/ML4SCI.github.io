---
title: Semi-supervised Symmetry Discovery
layout: gsoc_proposal
project: SYMMETRY
year: 2025
organization:
  - Alabama
  - NISER

---

## Description
Recent success in the domain of unsupervised and semi-supervised learning has been lately a pivotal factor for development of Physics Aware and Symmetry Aware Machine Learning techniques where a model learns the symmetry of a dataset as a meta task and ends up learning the physics through the same.

Although most of the symmetries that we work with for SM physics are well defined and formulated, they can be well interpreted in 4-vector or 4-momenta basis. With change of representation the symmetries become elusive and difficult to write and work with. This calls for machine learning techniques that can learn the representation of the given symmetry through the means of a conserved quantity for a given abstract representation space.

Learning these symmetries not only makes us more prepared to deal with the physics constraints in these abstract spaces and coordinates but also makes us able to build neural networks that are invariant to these symmetries. Such neural networks as seen from the existing literature are more robust, stable, interpretable and data efficient.

This project will focus on ways to learn the symmetries using semi-supervised approaches for the raw CMS calorimetric data stream.

## Duration
Total project length: 175/350 hours.

## Task ideas
  * Build an understanding of the symmetries present and their nature of representation on the CMS detector space [link](https://arxiv.org/abs/2104.09459).
  * Develop a supervised model to learn some of the symmetries given the conserved quantity and nature of augmentations.
  * Extend the supervised approach to a semi-supervised setup to discover symmetries without using the augmentation space [link](https://arxiv.org/abs/2302.00236).
  * [Advanced Step] Using the symmetries discovered to build physics to build a physics-aware neural network.

## Expected results
  * Discover hidden symmetries present in the CMS dataset.
  * Benchmark the models with other previous works in terms of data efficiency and invariance with respect to symmetry operations.

## Difficulty level
Advanced

## Requirements
* Proficiency in C++, Python
* Experience with PyTorch and TensorFlow
* Previous experience in Deep Learning

<!-- ## Test
Please use [this link](https://docs.google.com/document/d/1QuG0Ho3pWsJGMx0fG969aBNfgPg-cDxU9w33ZuDEBng/edit?usp=sharing) to access the test for this project. -->

## Mentors
  * [Diptarko Choudhury](mailto:ml4-sci@cern.ch) (NISER)
  * [Sergei Gleyzer](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Ruchi Chudasama](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Samuel Campbell](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Emanuele Usai](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Alex Roman](mailto:ml4-sci@cern.ch) (University of Alabama)

Please **DO NOT** contact mentors directly by email. Instead, please email [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch) with Project Title and **include your CV** and **test results**. The mentors will then get in touch with you.

## Links
  * [Paper 1](https://arxiv.org/abs/2302.00236)
  * [Paper 2](https://arxiv.org/abs/2104.09459)
