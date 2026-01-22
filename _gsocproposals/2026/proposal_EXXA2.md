---
title: Denoising Astronomical Observations of Protoplanetary Disks
layout: gsoc_proposal
project: EXXA
year: 2026
organization:
 - University of Alabama
 - Oxford University
---

#### Description

Recent advancements in observational astronomy have given the field the ability to resolve protoplanetary disks, the sites of planet formation, in unprecendeted detail. Array telescopes, such as ALMA and VLT, produce data that have revolutionized the study of these environments, spurring a rapid increase in the number of observations, significant advancements in theoretical understandings of planet formation processes, and the need for more efficient and accurate data processing. Traditional data processing algorithms, while advanced and powerful, are often time-consuming, computationally expensive, and can still produce noisy results. State-of-the-art machine learning algorithms, such as diffusion networks, are well-suited to this task and are a prime candidate for implementation in the field of protoplanetary disk astronomy. The purpose of this project is to develop machine learning algorithms to create a pipeline that denoises observational data more quickly and to a greater extent than current methods.

#### Duration

Total project length: 175/350 hours.

#### Task Ideas

  - Use synthetic observations of protoplanetary disks created using hydrodynamic simulations and radiative transfer to train machine learning models capable of denoising observational data.
  - Investigate and select suitable machine learning denoising models that can handle the complexity and heterogeneity of the data.
  - Develop a training pipeline that includes data augmentation techniques to enrich the training dataset and improve model robustness.
  - Implement the model and train it on the prepared dataset, optimizing for the ability to reproduce the raw synthetic observations.
  - Generalize the model to other types of observations, including line emission data and observations from other telescopes.
  - Validate the model's performance on real observational data from ALMA and VLT, comparing the performance to traditional methods.

#### Expected Results

  - A machine learning denoising model tailored for removing noise from astronomical observations, leveraging the unique characteristics of observational data.
  - A detailed analysis of the model's performance in removing noise from the data, including comparisons to traditional data processing methods and real observational data.
  - A publicly available dataset curated for training and testing the model, accompanied by a comprehensive data preprocessing and augmentation pipeline.
  - Documentation outlining the model architecture, training process, and guidelines for application to new datasets, ensuring reproducibility and facilitating future research in the field.


## Requirements

* Python, PyTorch, C/Fortran
* Background in astronomy is a bonus but not a requirement

## Test
Use [this link](https://docs.google.com/document/d/1t2cSxEx3vIa6uirfkMkF92rWZM4tTJ_V-lkpYSdukVQ/edit?usp=sharing) for instructions on completing the test.

## Links

* [Previous Paper 1](https://iopscience.iop.org/article/10.3847/1538-4357/aca477)
* [Previous Paper 2](https://iopscience.iop.org/article/10.3847/1538-4357/acc737)

## Mentors

* [Sergei Gleyzer](mailto:ml4-sci@cern.ch) (University of Alabama)
* [Jason Terry](mailto:jpterry@uga.edu) (Oxford University)

Please **DO NOT** contact mentors directly by email. Instead, please email [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch) with Project Title and **include your CV**. The mentors will then get in touch with you.
