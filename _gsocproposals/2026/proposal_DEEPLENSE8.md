---
title: Neural Operators for Fast Simulation of Strong Gravitational Lensing
layout: gsoc_proposal
project: DEEPLENSE
project size: 350hr
year: 2026
organization:
  - Alabama
  - MIT
---

## Description

Strong gravitational lensing is a powerful probe of dark matter substructure and cosmological structure formation. Current simulation pipelines (e.g., Lenstronomy-based ray tracing) require solving the lens equation repeatedly for different mass distributions and source configurations. While accurate, these simulations are computationally expensive and limit large-scale parameter sweeps, uncertainty quantification, and real-time inference.
This project proposes the development of a Neural Operator framework to learn the functional mapping between mass distributions and lensed images. Unlike traditional neural networks that operate on finite-dimensional vectors, neural operators learn mappings between infinite-dimensional function spaces. This makes them particularly well-suited for approximating solutions of physical systems governed by partial differential equations.
The goal is to train a neural operator that directly maps:
  * Lens mass distribution → Lensed image
  or
  * (Mass distribution, source light profile) → Observed lensed image


Such a model would serve as a fast surrogate simulator capable of producing high-fidelity lensing outputs at a fraction of the computational cost of traditional ray-tracing solvers.
This would represent the first exploration of neural operators within the ML4SCI DeepLense ecosystem.


## Duration

Total project length: 175/350 hours.

## Difficulty level

Advanced

## Task ideas
1. Literature Study
    1. Study Fourier Neural Operators (FNO)
    2. Study DeepONets
    3. Review operator learning in physical systems
2. Neural Operator Implementation
    1. Implement Fourier Neural Operator for 2D fields
    2. Compare with DeepONet-style architectures
    3. Explore spectral vs spatial operator parameterizations
3. Evaluation
    1. Compare speed vs traditional solver
    2. Measure pixel-wise reconstruction error
    3. Evaluate preservation of physical invariants
    4. Test generalization across:
        1. Different mass profiles
        2. Different redshifts
        3. Different source morphologies
4. Extensions (if time permits)
    1. Conditional neural operators
    2. Uncertainty-aware operator learning
    3. Physics-informed operator constraints
    4. Hybrid operator + diffusion refinement




## Expected results
 * A neural operator capable of approximating the lensing simulation operator.
 * Significant speedup compared to ray-tracing pipelines.
 * Demonstration of generalization across varying astrophysical conditions.
 * A benchmark study comparing neural operators with CNN-based surrogate models.



## Requirements
Python, PyTorch, experience with machine learning and deep learning.
Partial understanding of:
  * Representation learning
  * Spectral methods
  * Partial differential equations (basic familiarity)
  * Scientific machine learning concepts
Familiarity with gravitational lensing is preferred but not mandatory.



<!---
## Test
Please use this [link](https://docs.google.com/document/d/1a-5JiHph3K59gV3-kEZWzKYTFMvDeYiJvoE0U2I4x0w/edit?usp=sharing) to access the test for this project.
--->

## Mentors
  * [Michael Toomey](mailto:ml4-sci@cern.ch) (Massachusetts Institute of Technology)
  * [Sergei Gleyzer](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Pranath Reddy](mailto:ml4-sci@cern.ch) (University of Florida)
  * [Ashutosh Ojha](mailto:ml4-sci@cern.ch) (Indian Institute of Technology (Indian School of Mines), Dhanbad)


Please **DO NOT** contact mentors directly by email. General questions can be directed to [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch). To submit your proposal, CV, and test task solutions, please use [this Google form](https://forms.gle/SPXo8kSwHHptcBmk9).


## Links
  * [Paper 1](https://arxiv.org/abs/2010.08895)
  * [Paper 2](https://arxiv.org/abs/2108.08481)
  * [Paper 3](https://arxiv.org/abs/1910.03193)
  