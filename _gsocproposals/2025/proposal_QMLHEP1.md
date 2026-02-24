---
title: Implementation of Quantum Generative Adversarial Networks to Perform High Energy Physics Analysis at the LHC
layout: gsoc_proposal
project: QMLHEP
year: 2025
organization:
 - Alabama
 - Wisconsin
 - TUM
 - BitsPilani
 - BUAP
---

## Description
The ambitious HL-LHC program will require enormous computing resources in the next two decades. New technologies are being sought to replace the present computing infrastructure. A burning question is whether quantum computers can solve the ever-growing demand for computing resources in High-Energy Physics (HEP) in general and physics at LHC in particular. 

Discovery of new physics requires the identification of rare signals in immense backgrounds. The development of machine learning methods will greatly enhance our ability to achieve this objective. 

With this project we seek to implement Quantum Machine Learning methods for LHC HEP analysis based on the Pennylane framework. This will enhance the ability of the HEP community to use Quantum Machine Learning methods.

## Duration

Total project length: 175/350 hours.

## Task ideas
  * Implement a Quantum Generative Adversarial Network (QGAN) based on a suitable framework, e.g. Pennylane. See e.g. papers for possible models under ‘Links’
  * Verify that it works and no mode collapse happens using the MNIST dataset.
  * Apply the quantum machine learning method to one LHC flagship physics channel (e.g. double-Higgs production). Compare the quantum machine learning performance to the classical machine learning performance.
  * Train a classical GAN and a QGAN on exactly the same tasks and datasets, serving as a direct benchmark. Measure differences in training speed, and the fidelity or quality of generated samples.
  * Develop and implement a QGAN that successfully captures the underlying, or “implicit,” probability distribution of the training data and compare the generated and real distributions using distribution-similarity measures.

 
## Expected results
  * Trained Quantum Generative Adversarial Network method based on e.g. Pennylane framework.
  * Successfully apply the Quantum Machine Learning method to LHC physics analyses and obtain performance benchmarks to compare to classical machine learning methods.
  * A comprehensive comparison of the training time, mode collapse frequency, sample quality scores between QGAN and classical GAN.
  * Demonstrate that the QGAN can produce samples whose statistical properties match those of the real dataset.

 
<!---
## Test
Please use [this link](https://docs.google.com/document/d/1imoMEyC0r5IESonwgA7BThEQWDfdrOsoyfMfyJgyXmU/edit?usp=sharing) to access the test for this project.
--->
  
## Requirements 
  * Solid knowledge of machine learning and deep learning
  * Knowledge of quantum mechanics
  * Strong python skills
  * Ability to work independently and proactive on a research project

## Difficulty Level
  * Intermediate/Advanced

## Mentors
  * [Rui Zhang](mailto:ml4-sci@cern.ch) (University of Wisconsin-Madison)
  * [Sergei Gleyzer](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Emanuele Usai](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Tom Magorsh](mailto:ml4-sci@cern.ch) (TUM)
  * [Abhay Kamble](mailto:ml4-sci@cern.ch) (BitsPilani) 
  * [Isabel Pedraza](mailto:ml4-sci@cern.ch) (Benemérita Universidad Autónoma de Puebla)

## Links
  * [HL-LHC](https://hilumilhc.web.cern.ch)
  * [LHC](https://home.cern/science/accelerators/large-hadron-collider)
  * [Pennylane](https://pennylane.ai)
  * [Paper 1](https://arxiv.org/abs/2105.00080) 
  * [Paper 2](https://arxiv.org/abs/2210.16857)

Please **DO NOT** contact mentors directly by email. General questions can be directed to [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch). To submit your proposal, CV, and test task solutions, please use [this Google form](https://forms.gle/SPXo8kSwHHptcBmk9).
