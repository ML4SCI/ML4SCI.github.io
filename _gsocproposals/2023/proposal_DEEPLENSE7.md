---
title: Self-Supervised Learning for Strong Gravitational Lensing
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

Strong gravitational lensing is a promising probe of the substructure of dark matter to better understand its underlying nature. Deep learning methods have the potential to accurately identify images containing substructure, and differentiate WIMP particle dark matter from other well-motivated models, including axions and axion-like particles, warm dark matter etc. 

Supervised classification can be difficult when the number of known objects of a particular class is very small. This is usually the case for strong gravitational lensing images, where the number of samples from one or more classes are relatively lower than others. Self-supervised learning (SSL) has proven to outperform standard supervised machine learning models, particularly when the number of data labels available for supervision is low. Moreover, SSL can take advantage of very large unlabelled datasets that would be difficult or impossible to label manually and build meaningful representations. To date, only convolutional neural networks (CNNs) have been used with the SSL technique for strong gravitational lensing data. Transformers or hybrid models (Transformers + CNN) promise more robustness for representation learning but have not been addressed by the community. 
This project will focus on the development of self-supervised learning techniques with Transformers for strong gravitational lensing data. Furthermore, we will also investigate equivariant techniques in the self-supervised learning context for other strong lensing tasks.


## Duration

Total project length: 175 hours.

## Task ideas
 * Explore the use of Transformers/Hybrid architectures with self-supervised learning for representation learning. The trained model can then be fine-tuned for specific tasks such as regression or classification.
 * Explore the use of Equivariant Transformers with self-supervised learning for representation learning. The trained model could then be fine-tuned for specific tasks such as regression or classification.
 * Expand the DeepLense functionality with self-supervised learning algorithms suitable for computer vision tasks applicable to strong gravitational lensing data.

## Expected results
 *  Develop a self-supervised learning transformer model for DeepLense training and inference.

## Requirements
Python, PyTorch and relevant past experience in Machine Learning. 

## Test
Test will become live after GSoC Orgs are announced
<!-- ## Test
Please use this [link](https://docs.google.com/document/d/1y9-F1Z8iz_GvVRL9lQmMKlbq3ID3spiW0npe1s1fXwg/edit?usp=sharing) to access the test for this project.  -->

## Mentors
  * [Michael Toomey](mailto:ml4-sci@cern.ch) (Brown University)
  * [Pranath Reddy](mailto:ml4-sci@cern.ch) (BITS Pilani Hyderabad)
  * [Sergei Gleyzer](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Emanuele Usai](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Saranga Mahanta](mailto:ml4-sci@cern.ch) (Institut Polytechnique de Paris)
  * [Karthik Sachdev](mailto:ml4-sci@cern.ch) (RWTH Aachen)


Please DO NOT contact mentors directly by email. Instead, please email [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch) with Project Title and include **your CV** and **test results**. The relevant mentors will then get in touch with you. 


## Links
  * [Paper 1](https://arxiv.org/abs/2008.12731)
  * [Paper 2](https://arxiv.org/abs/1909.07346)
  * [Paper 3](https://arxiv.org/abs/2112.12121)
