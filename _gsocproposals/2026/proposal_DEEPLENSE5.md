---
title: Physics-Informed Diffusion Models for Gravitational Lensing Simulation
layout: gsoc_proposal
project: DEEPLENSE
project size: 175hr/350hr
year: 2026
organization:
  - Alabama
  - MIT
  - Florida
---

## Description

Strong gravitational lensing is a promising probe of the substructure of dark matter to better understand its underlying nature. Deep learning methods have the potential to accurately identify images containing substructure and differentiate WIMP particle dark matter from other well-motivated models, including axions and axion-like particles, warm dark matter, etc. 
This project proposes the development of physics-informed diffusion and flow matching models for simulating strong gravitational lensing images. Gravitational lensing is governed by well-defined physical laws and symmetries. We aim to explore strategies for encoding these physical structures directly into generative models so that outputs are not merely statistically realistic but physically consistent. Possible directions include incorporating symmetry-aware architectures, parameterizing the generation process through physically meaningful intermediate representations (e.g., convergence and shear maps), enforcing governing equations as soft or hard constraints, or other approaches the contributor may propose.
The resulting model is intended to produce high-fidelity, physics-compliant lensing simulations to augment training data for substructure detection and dark matter classification, while offering stronger generalization and a narrower sim-to-real gap compared to purely data-driven generative approaches.

## Duration

Total project length: 175/350 hours.

## Difficulty level
Intermediate/Advanced

## Task ideas
 * Explore diffusion models for the generation of strong gravitational lensing images.
 * Benchmark generated images against traditional simulations for physical consistency and downstream task utility.
 * Create a diverse dataset of simulated gravitational lensing images under various astrophysical conditions.


## Expected results
 *  A diffusion model capable of generating realistic, physically consistent simulations of strong gravitational lensing phenomena.

## Requirements
 * Python, PyTorch and relevant past experience in Machine Learning.
 * Familiarity with astrophysics and gravitational lensing is preferred but not required.

<!---
## Test
Please use this [link](https://docs.google.com/document/d/1a-5JiHph3K59gV3-kEZWzKYTFMvDeYiJvoE0U2I4x0w/edit?usp=sharing) to access the test for this project.
--->

## Mentors
  * [Michael Toomey](mailto:ml4-sci@cern.ch) (Massachusetts Institute of Technology)
  * [Pranath Reddy](mailto:ml4-sci@cern.ch) (University of Florida)
  * [Sergei Gleyzer](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Hamees Sayed](mailto:ml4-sci@cern.ch) (IIT Madras)

Please DO NOT contact mentors directly by email. Instead, please email [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch) with Project Title and include **your CV** and **test results**. The relevant mentors will then get in touch with you. 


## Links
  * [Paper 1](https://arxiv.org/abs/2008.12731)
  * [Paper 2](https://arxiv.org/abs/1909.07346)
  * [Paper 3](https://arxiv.org/abs/2112.12121)
  * [Paper 4](https://arxiv.org/abs/2203.17003)
  * [Paper 5](https://arxiv.org/abs/2211.03812)
