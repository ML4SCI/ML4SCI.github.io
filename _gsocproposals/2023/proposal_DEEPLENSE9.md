---
title: Search for Strong Gravitational Lenses
layout: gsoc_proposal
project: DEEPLENSE
project size: 175hr
year: 2023
organization:
  - Alabama
  - Brown
  - BITS Pilani Hyderabad
  - Paris
  - RWTH
---

## Description

Strong gravitational lensing is a powerful tool in exploring various astrophysical questions, including probing the substructure in dark matter haloes of the lensing galaxies. However one of the main limitations of such analysis is the relatively small number of known lens candidates and confirmed lens systems. Recent works have shown the potential of CNNs in the task of lens finding — classification of images obtained from the telescopes into lensed and non-lensed systems. Since the number of real lenses is insufficient for training a machine learning algorithm, training datasets heavily rely on simulations.  Even though simulated systems are designed to resemble observational data as closely as possible, there is still a need to bridge the gap between simulated data used for training and real images showing a wider variety of object morphologies. 

The goal of this project is to develop and test methods to identify lensed systems in the data from wide-area surveys (such as Hyper Suprime-Cam or Dark Energy Survey) with the focus on applying domain adaptation techniques with simulated data as source and real observational images as target.  



## Duration

Total project length: 175/350 hours.

## Task ideas
 * Explore the use of domain adaptation methods for lens finding. 


## Expected results
 *  Develop a model for lens finding and apply it to real observational data. 

## Requirements
Python, PyTorch and relevant past experience in Machine Learning.

## Test
Please use this [link](https://docs.google.com/document/d/1y9-F1Z8iz_GvVRL9lQmMKlbq3ID3spiW0npe1s1fXwg/edit?usp=sharing) to access the test for this project.
**The test is due by April 3rd, however please keep in mind that it takes about 1 week to craft a good proposal and proposals need to be submitted via GSoC portal by April 4**

## Mentors
  * [Michael Toomey](mailto:ml4-sci@cern.ch) (Brown University)
  * [Sergei Gleyzer](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Emanuele Usai](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Anna Parul](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Pranath Reddy](mailto:ml4-sci@cern.ch) (Bits Pilani Hyderabad)
  * [Saranga Mahanta](mailto:ml4-sci@cern.ch) (Institut Polytechnique de Paris)
  * [Karthik Sachdev](mailto:ml4-sci@cern.ch) (RWTH Aachen)


Please DO NOT contact mentors directly by email. Instead, please email [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch) with Project Title and include **your CV** and **test results**. The relevant mentors will then get in touch with you. 


## Links
  * [Paper 1](https://arxiv.org/abs/2008.12731)
  * [Paper 2](https://arxiv.org/abs/1909.07346)
  * [Paper 3](https://arxiv.org/abs/2112.12121)