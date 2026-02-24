---
title: Equivariant Vision Networks for Predicting Planetary Systems' Architectures
layout: gsoc_proposal
project: EXXA
year: 2025
organization:
 - University of Alabama
 - Oxford University
---

#### Description

The architecture of planetary systems, including the number of planets and their orbital configurations, provides crucial insights into their formation and evolution. This project aims to leverage the capabilities of equivariant computer vision networks to predict the number of planets in observed systems from astronomical data. Equivariant networks, due to their ability to handle rotational and reflectional symmetries inherent in astronomical images, offer a promising approach for analyzing spatial data without loss of predictive accuracy due to orientation changes. By regressing on the number of planets, this project seeks to develop a robust model that can adapt to the complexities of observational data, including direct images, transit data, and radial velocity measurements.

#### Duration

Total project length: 175/350 hours.

#### Task Ideas

  - Review and implement state-of-the-art equivariant neural network architectures suitable for astronomical data analysis.
  - Curate a dataset from existing astronomical surveys, including labeled systems with known numbers of planets, for training and testing the model.
  - Train the equivariant network on the curated dataset, optimizing for accurate regression on the number of planets in a system.
  - Evaluate the model's performance using a separate test set, focusing on its ability to generalize across different types of planetary systems and observational techniques.
  - Explore the integration of additional data modalities (e.g., spectroscopic data) to improve the model's predictive capabilities.

#### Expected Results

  - A highly accurate equivariant computer vision model capable of regressing on the number of planets in observed systems, accounting for the complexities and variabilities in astronomical data.
  - A comprehensive evaluation of the model's performance, highlighting its strengths and potential areas for improvement.
  - Documentation and guidelines for applying the model to new datasets, facilitating further research and potential real-world applications in exoplanet discovery and characterization.

## Requirements

* Python, PyTorch, C/Fortran
* Background in astronomy is a bonus but not a requirement

## Test
Use [this link](https://docs.google.com/document/d/1t2cSxEx3vIa6uirfkMkF92rWZM4tTJ_V-lkpYSdukVQ/edit?usp=sharing) for instructions on completing the test.

## Links

* [Previous Paper 1](https://iopscience.iop.org/article/10.3847/1538-4357/aca477)
* [Previous Paper 2](https://iopscience.iop.org/article/10.3847/1538-4357/acc737)
* [Previous Paper 3](https://nips.cc/virtual/2023/76224)

## Mentors

* [Sergei Gleyzer](mailto:ml4-sci@cern.ch) (University of Alabama)
* [Jason Terry](mailto:jpterry@uga.edu) (Oxford University)
* [Emily Panek](mailto:ml4-sci@cern.ch) (University of Alabama)
* [Alex Roman](mailto:ml4-sci@cern.ch) (University of Alabama)

Please **DO NOT** contact mentors directly by email. General questions can be directed to [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch). To submit your proposal, CV, and test task solutions, please use [this Google form](https://forms.gle/SPXo8kSwHHptcBmk9).
