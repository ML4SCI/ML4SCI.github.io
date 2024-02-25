---
title: Search for Strong Gravitational Lenses 
layout: gsoc_proposal
project: DEEPLENSE
project size: 175hr
year: 2024
organization:
  - Alabama
  - Brown
  - BITS Pilani Hyderabad
  - Paris
  - RWTH
---

## Description

Strong gravitational lensing is a powerful tool in exploring various astrophysical questions, including probing the substructure in dark matter haloes of the lensing galaxies. However one of the main limitations of such analysis is the relatively small number of known lens candidates and confirmed lens systems. 

Recent works have shown the potential of CNNs in the task of lens finding — classification of images obtained from the telescopes into lensed and non-lensed systems. Since the number of real lenses is insufficient for training a machine learning algorithm, training datasets heavily rely on simulations. However it has been noticed that CNNs perform worse on lens images obtained with the instrument from the one that simulations were tailored to reproduce (for example, different surveys use different color filters and have different resolution).

The goal of this project is to investigate the prospects of using domain adaptation techniques to bridge the gap between simulated data used for training and real images from different surveys (such as [HSC-SSP](https://hsc.mtk.nao.ac.jp/ssp/), [HST](https://science.nasa.gov/mission/hubble/), [DES](https://www.darkenergysurvey.org), [JWST](https://webb.nasa.gov), and future missions) and explore which type of lenses has a higher risk of being lost during the automated searches.

## Duration

Total project length: 175/350 hours.

## Difficulty level

Intermediate

## Task ideas
 * Compare the performance of supervised neural networks with various architectures (convolutional, residual, equivariant) on the simulated dataset.
 * For the best model explore the use of domain adaptation techniques in application to real data
   
## Expected results
 *  Develop a model for lens finding and apply it to real observational data.

## Requirements
Python, PyTorch and relevant past experience in Machine Learning. 

## Test
Please use this [link](https://docs.google.com/document/d/1P8SC5bh7twrWta4MD8jpn5kwEmoIAYlDd39iVWRkkq8/edit?usp=sharing) to access the test for this project.

## Mentors
  * [Michael Toomey](mailto:ml4-sci@cern.ch) (Massachusetts Institute of Technology)
  * [Anna Parul](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Sergei Gleyzer](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Pranath Reddy](mailto:ml4-sci@cern.ch) (BITS Pilani Hyderabad)
  * [Saranga Mahanta](mailto:ml4-sci@cern.ch) (Institut Polytechnique de Paris)
  * [Kartik Sachdev](mailto:ml4-sci@cern.ch) (RWTH Aachen)


Please DO NOT contact mentors directly by email. Instead, please email [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch) with Project Title and include **your CV** and **test results**. The relevant mentors will then get in touch with you. 


## Links
  * [Paper 1](https://arxiv.org/abs/2008.12731)
  * [Paper 2](https://arxiv.org/abs/1909.07346)
  * [Paper 3](https://arxiv.org/abs/2112.12121)
