---
title: Learning quantum representations of classical high energy physics data with contrastive learning
layout: gsoc_proposal
project: QMLHEP
year: 2025
organization:
 - Alabama
 - Wisconsin
 - TUM
---

## Description
The ambitious [HL-LHC](https://hilumilhc.web.cern.ch) program will require enormous computing resources in the next two decades. New technologies are being sought after to replace the present computing infrastructure. A burning question is whether quantum computer can solve the ever growing demand of computing resources in High Energy Physics (HEP) in general and physics at [LHC](https://home.cern/science/accelerators/large-hadron-collider) in particular. Our goal here is to explore and to demonstrate that Quantum Computing can be the new paradigm (Proof of Principle).

Discovery of new physics requires the identification of rare signals against immense backgrounds. Development of machine learning methods will greatly enhance our ability to achieve this objective. However, with this ever-growing volume of data in the near future, current machine learning algorithms will require large computing resources and excessive computing time to achieve good performance. Quantum Computing in Qubit platform, where qubits are used instead of bits in classical computer, has the potential to improve the time complexity of classical algorithms.

With this project we seek to implement Quantum Machine Learning methods for LHC HEP analysis based on e.g. the Pennylane framework. This will enhance the ability of the HEP community to use Quantum Machine Learning methods.

## Duration

Total project length: 175/350 hours.

## Task ideas
  * Implement a trainable embedding function to encode classical data onto a quantum model with contrastive learning. Try and develop different ideas for embedding functions and contrastive losses for training.
  * Benchmark the trained embedding against a standard encoding on a given QML model (e.g. a QCNN).
 
## Expected results
  * Trained embedding function for classical data with e.g. Pennylane framework.
  * Benchmark of the performance against a standard encoding
  

## Test
Please use [this link](https://docs.google.com/document/d/1imoMEyC0r5IESonwgA7BThEQWDfdrOsoyfMfyJgyXmU/edit?usp=sharing) to access the test for this project.
  
## Requirements
  * Solid knowledge of machine learning and deep learning
  * Knowledge of quantum mechanics desired
  * Strong python skills
  * Ability to work independently and proactive on a research project 

## Difficulty Level
  * Intermediate/Advanced

## Mentors
  * [Rui Zhang](mailto:ml4-sci@cern.ch) (University of Wisconsin-Madison)
  * [Alkaid Cheng](mailto:ml4-sci@cern.ch) (University of Wisconsin Madison)
  * [Sergei Gleyzer](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Emanuele Usai](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Tom Magorsh](mailto:ml4-sci@cern.ch) (TUM)

## Links
  * [HL-LHC](https://hilumilhc.web.cern.ch)
  * [LHC](https://home.cern/science/accelerators/large-hadron-collider)
  * [Pennylane](https://pennylane.ai)
  * [Paper 1](https://iopscience.iop.org/article/10.1088/2058-9565/ac6825)
  * [Paper 2](https://arxiv.org/abs/2008.08605)

Please **DO NOT** contact mentors directly by email. Instead, please email [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch) with Project Title and **include your CV** and **test results**. The mentors will then get in touch with you.
