---
title: Diffusion Models for Gravitational Lensing Simulation
layout: gsoc_proposal
project: DEEPLENSE
project size: 175hr/350hr
year: 2025
organization:
  - Alabama
  - MIT
  - Florida
---

## Description

Strong gravitational lensing is a promising probe of the substructure of dark matter to better understand its underlying nature. Deep learning methods have the potential to accurately identify images containing substructure and differentiate WIMP particle dark matter from other well-motivated models, including axions and axion-like particles, warm dark matter, etc.

Traditional simulations of gravitational lensing are time-consuming and require extensive computational resources. This project proposes the use of diffusion models, a class of generative models known for their ability to produce high-quality, detailed images from a distribution of noise, to simulate strong gravitational lensing images. We aim to generate realistic simulations of gravitational lensing events that can be used to augment datasets for machine learning models and facilitate the development of better domain adaptation and self-supervised models aimed at bridging the gap between simulated and real images of gravitational lensing. Furthermore, we will also investigate leveraging conditional diffusion models to generate gravitational lensing simulations by conditioning the model on specific parameters related to the lensing events, such as the mass distribution of the lensing galaxy, orientation, and the redshift of both the source and the lens.

## Duration

Total project length: 175/350 hours.

## Difficulty level

intermediate
Intermediate/Advanced

## Task ideas
 * Explore diffusion models for the generation of strong gravitational lensing images.
 * Create a diverse dataset of simulated gravitational lensing images under various astrophysical conditions.

## Expected results
 *  A diffusion model capable of generating realistic simulations of strong gravitational lensing phenomena.

## Requirements
 * Python, PyTorch and relevant past experience in Machine Learning.
 * Familiarity with astrophysics and gravitational lensing is preferred but not required.

## Test
Please use this [link](https://docs.google.com/document/d/1a-5JiHph3K59gV3-kEZWzKYTFMvDeYiJvoE0U2I4x0w/edit?usp=sharing) to access the test for this project.

## Mentors
  * [Michael Toomey](mailto:ml4-sci@cern.ch) (Massachusetts Institute of Technology)
  * [Pranath Reddy](mailto:ml4-sci@cern.ch) (University of Florida)
  * [Sergei Gleyzer](mailto:ml4-sci@cern.ch) (University of Alabama)

Please DO NOT contact mentors directly by email. Instead, please email [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch) with Project Title and include **your CV** and **test results**. The relevant mentors will then get in touch with you. 


## Links
  * [Paper 1](https://arxiv.org/abs/2008.12731)
  * [Paper 2](https://arxiv.org/abs/1909.07346)
  * [Paper 3](https://arxiv.org/abs/2112.12121)
