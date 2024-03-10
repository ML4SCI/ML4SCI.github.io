---
title:  Continuous learning for data quality monitoring at particle colliders
layout: gsoc_proposal
project: ML4DQM
year: 2024
organization:
  - Alabama

---

## Description


One key challenge in models currently used in Machine Learning do Data Quality Monitoring is that such models are often limited in their transferability to other systems, meaning each system or sub-detector within large HEP detectors need to have individual models developed, tested, and deployed, which can take significant time and effort. Furthermore, as detectors age, the data they produce can exhibit expected variations, potentially leading to misclassification as ‘bad data’ when ML models performing DQM have been trained on pristine detector data.
This proposal seeks to address these challenges by pioneering continuous learning ML models that leverage ensemble learning techniques that are collectively able to adapt to both changing detector conditions, as well as changing detector systems.


## Duration

Total project length: 175 hours.

## Task ideas
 * Develop ensemble learning ML models using CMS data for the electromagnetic calorimeter (ECAL) sub-system.
 * Build and train the overall models and to demonstrate their performance on one single sub-system.

## Expected results
 * Build an ensemble learning ML model and demonstrate performance comparable or superior to human operator monitoring.
 * Validate the development of these models by using data instead acquired using the Tracker sub-system. The purpose of this task is to demonstrate the ability to take the overall architecture of the model but to train it with data from a different sub-system and evaluate its performance.

## Requirements
C++, Python, PyTorch, Tensorflow and some previous experience in Deep Learning.

## Project difficulty level
Challenging

## Mentors
  * [Emanuele Usai](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Sergei Gleyzer](mailto:ml4-sci@cern.ch) (University of Alabama)


## Test
Solve the evaluation task(s) for any of the other projects in the ML4SCI umbrella organization.  Please send us your CV and a link to all your completed work (github repo, Jupyter notebook + pdf of Jupyter notebook with output) to [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch) with Evaluation Test: ML4DQM in the title. In the email specify which evaluation test(s) you solved. 

Please **DO NOT** contact mentors directly by email. Instead, please email [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch) with Project Title and **include your CV** and **test results**. The mentors will then get in touch with you.


