---
title: Regression on Planetary Mass in Protoplanetary Disks
layout: gsoc_proposal
project: EXXA
year: 2024
organization:
 - University of Alabama
---

#### Description

The mass of planets forming within protoplanetary disks is a fundamental parameter that influences their evolution, atmospheric composition, and potential for hosting life. This project proposes to develop a machine learning model that can accurately regress on the mass of planets observed in protoplanetary disks. Utilizing observational data, including disk morphology, spectral signatures, and dynamical interactions within the disk, the model will aim to predict the mass of forming planets. This approach addresses the challenge of directly measuring planetary masses in these environments, offering a novel tool for astronomers to infer planet formation processes and disk-planet interactions.

#### Duration

Total project length: 175/350 hours.

#### Task Ideas

  - Analyze and preprocess observational data from telescopes such as ALMA and the VLT, focusing on features relevant to planet mass estimation.
  - Investigate and select suitable machine learning regression models that can handle the complexity and heterogeneity of the data.
  - Develop a training pipeline that includes data augmentation techniques to enrich the training dataset and improve model robustness.
  - Implement the model and train it on the prepared dataset, optimizing for accuracy in predicting planetary masses.
  - Validate the model's performance on a separate dataset of known planetary masses within protoplanetary disks, analyzing its effectiveness and areas for improvement.

#### Expected Results

  - A machine learning regression model tailored for estimating the mass of planets within protoplanetary disks, leveraging the unique characteristics of observational data.
  - A detailed analysis of the model's performance, including accuracy, precision, and recall in predicting planetary masses, as well as comparisons to traditional estimation methods.
  - A publicly available dataset curated for training and testing the model, accompanied by a comprehensive data preprocessing and augmentation pipeline.
  - Documentation outlining the model architecture, training process, and guidelines for application to new datasets, ensuring reproducibility and facilitating future research in the field.


## Requirements

* Python, PyTorch, C/Fortran
* Background in astronomy is a bonus but not a requirement

<!-- ## Test
Use [this link](https://docs.google.com/document/d/10jZ7aubVkfkcpURQQnvrvbC7o3XgglsJwjS0UA7SRBE/edit?usp=sharing) for instructions on completing the test. -->

## Links

* [Previous Paper 1](https://iopscience.iop.org/article/10.3847/1538-4357/aca477)
* [Previous Paper 2](https://iopscience.iop.org/article/10.3847/1538-4357/acc737)

## Mentors

* [Sergei Gleyzer](mailto:ml4-sci@cern.ch) (University of Alabama)
* [Jason Terry](mailto:jpterry@uga.edu) (University of Georgia)

Please **DO NOT** contact mentors directly by email. Instead, please email [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch) with Project Title and **include your CV**. The mentors will then get in touch with you.
