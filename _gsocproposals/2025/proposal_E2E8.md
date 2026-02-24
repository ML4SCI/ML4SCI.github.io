---
title: Discovery of hidden symmetries and conservation laws
layout: gsoc_proposal
project: E2E
year: 2025
organization:
  - Alabama
  - NISER

---

## Description
Recent success in the domain of unsupervised and semi-supervised learning has been lately a pivotal factor for development of Physics Aware and Symmetry Aware Machine Learning techniques where a model learns the symmetry of a dataset as a meta task and ends up learning the physics through the same.

Although most of the symmetries that we work with for SM physics are well defined and formulated, they can be well interpreted in 4-vector or 4-momenta basis. With change of representation the symmetries become elusive and difficult to write and work with. This calls for machine learning techniques that can learn the representation of the given symmetry through the means of a conserved quantity for a given abstract representation space.

Learning these symmetries not only makes us more prepared to deal with the physics constraints in these abstract spaces and coordinates but also makes us able to build neural networks that are invariant to these symmetries. Such neural networks as seen from the existing literature are more robust, stable, interpretable and data efficient.

This project will focus on ways to learn hidden symmetries combining the works of
* https://arxiv.org/abs/2109.09721
* https://arxiv.org/pdf/2301.05638v1 
* https://arxiv.org/abs/2302.00236

## Duration
Total project length: 175/350 hours.

## Task ideas
  * Develop a deep learning model capable of uncovering the symmetries present in the toy datasets and then extending it to more abstract use cases.
  * Using the symmetries discovered to probe the phase space of the CMS datasets.
  * Building physics aware models using the symmetries.

## Expected results
  * Discover symmetries and conserved quantities present in the CMS dataset.
  * Benchmark the models with other previous works in terms of data efficiency and invariance with respect to symmetry operations.

## Difficulty level
Advanced

## Requirements
* Proficiency in C++, Python
* Experience with PyTorch and TensorFlow
* Previous experience in Deep Learning

<!---
## Test
Please use [this link](https://docs.google.com/document/d/10tITU-OJDtaZkLmXpoCpzIM55XcV4Z_7ykS7N9tyISA/edit?usp=sharing) to access the test for this project.
--->

## Mentors
  * [Diptarko Choudhury](mailto:ml4-sci@cern.ch) (NISER)
  * [Sergei Gleyzer](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Ruchi Chudasama](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Samuel Campbell](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Emanuele Usai](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Alex Roman](mailto:ml4-sci@cern.ch) (University of Alabama)

Please **DO NOT** contact mentors directly by email. General questions can be directed to [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch). To submit your proposal, CV, and test task solutions, please use [this Google form](https://forms.gle/SPXo8kSwHHptcBmk9).

## Links
  * [Paper 1](https://arxiv.org/abs/2109.09721)
  * [Paper 2](https://arxiv.org/pdf/2301.05638v1)
  * [Paper 3](https://arxiv.org/abs/2302.00236)
