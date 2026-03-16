---
title: Physics-informed neural network shape optimization
layout: gsoc_proposal
project: SPINN
year: 2026
organization:
  - Alabama
  - Cerium

---

## Description
In many engineering and physics domains, the shape or geometry of an object directly influences its performance with regard to some metric. Simple examples include the shape of an airplane wing affecting its lift-to-drag ratio, or the geometry/structure of a bridge influencing the maximum load weight which can safely traverse it. “Shape optimization” refers to the task of identifying the ideal shape/geometry of such an object which can maximize or minimize a metric of interest with respect to that object. This project looks to leverage Physics Informed Neural Networks (PINN) and Coordinate Projection Networks (also called shape networks in the literature) to develop machine learning architectures which can quickly and efficiently perform this task.

## Duration
Total project length: 175 hours.

## Task ideas
Recent research has demonstrated the feasibility of using PINNs (Paper 1) for performing shape optimization (Paper 2). Since that initial research, a number of techniques have been proposed and verified to help improve the performance of PINNs in general to overcome the shortcomings that generally plague PINNs: slow convergence, overfitting, and spectral bias in which low frequency solutions are preferentially converged towards during training. In particular, the use of grid-based structures (PIXEL, see Paper 3), and their further development into Physics-Informed Gaussians (PIG, see Paper 4), have improved upon many of these shortcomings. In this work, we look to apply these new techniques to the task of shape optimization. We additionally look to apply them to novel use-cases to demonstrate the usefulness of this approach. One use-case of particular interest is in the design optimization of Paul Traps, which are used in many applications ranging from quantum computing to mass spectrometry and atomic clocks (see Paper 5). The following task ideas are therefore proposed for this project:

  * Identify and implement the latest PINN techniques for the purpose of performing shape optimization, specifically the ones previously mentioned.
  * Identify relevant use-case scenarios and develop a PINN to accurately model the underlying physics. Paul Traps are of particular interest, however other use-cases will also be considered.
  * Perform model optimization of both PINN and coordinate projection network, with the intent of achieving superior performance with respect to relevant design metrics and computational complexity.

## Expected results:
  * PINN model with demonstrated ability to perform shape optimization.

## Difficulty level
Advanced

## Requirements
  * Essential: Experience in Python, PyTorch (or related ML framework), and machine learning are required. 
  * Preferred: Familiarity with basic physics concepts (classical mechanics, electromagnetics, etc.) at an undergraduate level. 
  * Will help you stand out: Experience performing physics simulations using standard simulation software (COMSOL, ANSYS, etc.) or an equivalent open source framework, and familiarity with associated concepts (numerical methods techniques, how to handle boundary conditions, etc.).

## Test
Please use [this link](https://docs.google.com/document/d/1mIyrMIo7NZSeKwQ2FQ1q3h1IVSPUkC0SHkREoklAcy8/edit?usp=sharing) to access the test for this project.

## Mentors
  * [Dale Julson](mailto:ml4-sci@cern.ch) (Cerium Labs)
  * [Eric Reinhardt](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Dinesh Ramakrishnan](mailto:ml4-sci@cern.ch) (University of Alabama)

Please **DO NOT** contact mentors directly by email. Questions should instead be directed to [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch) which is forwarded to mentors. To submit your proposal, CV, and test task solutions, please use [this Google form](https://forms.gle/SPXo8kSwHHptcBmk9).

## Links
  * [Paper 1](https://arxiv.org/abs/2201.05624)
  * [Paper 2](https://www.nature.com/articles/s41598-024-57137-4)
  * [Paper 3](https://arxiv.org/abs/2207.12800)
  * [Paper 4](https://arxiv.org/abs/2412.05994)
  * [Paper 5](https://arxiv.org/abs/1708.04689)
