---
title: Non-local GNNs for Jet Classification
layout: gsoc_proposal
project: GENIE
year: 2026
organization:
 - Alabama
 - EPFL
 - Princess Sumaya University for Technology
 - BITS Pilani Goa
---

## Description
In the search for new physics at the [Large Hadron Collider (LHC)](https://home.cern/science/accelerators/large-hadron-collider) a possible approach is to employ anomaly detection techniques to spot events that deviate from the standard model in an unsupervised manner. There have been many such studies using e.g. convolutional autoencoders. In previous GSoC projects, the usage of graph-based models has been very successful in generative tasks.Motivated by the success of graph-based models in various computational tasks, this project seeks to leverage non-local graph neural networks (GNNs) for the classification of jets in particle physics. Unlike conventional methods, which treat jets as independent entities, the proposed approach capitalizes on the inherent relational structure among particles within a jet, represented as a graph. The challenge is to account the long-range dependencies inherent to the jets, which regular GNNs fail to do. 


## Duration

Total project length: 175/350 hours.

## Difficulty Level
  * Intermediate/Advanced

## Task ideas
  * Develop a model for graph-based jet classification while accounting for long-range dependencies 
  * Benchmarking on benchmark datasets and comparison to a Transformer and regular MPNNs 
 
## Expected results
  * Trained graph-based jet classifier
  * Benchmarks on selected datasets

<!-- ## Test 
Please use [this link](https://docs.google.com/document/d/1lRJocBJ0MgrTTth07xAinz_2tZRgPJF6weVkR8TGPxI/edit?usp=sharing) to access the test for this project. -->
  
## Requirements 
  * Skills: Python, PyTorch or Keras and some previous experience in Machine Learning. 


## Mentors
  * [Sergei Gleyzer](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Ali Hariri](mailto:ml4-sci@cern.ch) (EPFL)
  * [Tom Magorsch](mailto:ml4-sci@cern.ch) (TUM)
 

## Links
  * [LHC](https://home.cern/science/accelerators/large-hadron-collider)

Please **DO NOT** contact mentors directly by email. Instead, please email [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch) with Project Title and **include your CV** and **test results**. The mentors will then get in touch with you.
