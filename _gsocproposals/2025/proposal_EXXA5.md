---
title: Foundation Models for Exoplanet Characterization
layout: gsoc_proposal
project: EXXA
year: 2025
organization:
 - University of Alabama
 - Oxford University
---

#### Description

The characterization of exoplanet atmospheres is crucial for understanding their compositions, weather patterns, and potential habitability. This project aims to develop machine learning models to analyze spectral data from exoplanets, identifying chemical abundances, cloud/haze structure and different atmospheric processes . The project will leverage data from telescopes and space missions, along with simulations of exoplanetary atmospheres under various conditions, to train and validate the models.

#### Duration

Total project length: 175/350 hours.

#### Task Ideas
  * Assemble a consolidated database using existing exoplanet transit observations from different instruments, spectral resolutions, and spectral ranges from publicly available exoplanet archives. 
  * Develop an ML approach to overcome the specific instrumental differences for the different observations. Training can be done on existing synthetic databases simulating the instrument performance (Hubble Space Telescope, JWST, Ariel etc.)
  * Apply the trained models to real observational data from Hubble, JWST, and future telescopes to characterize exoplanet atmospheres.
  * Explore the use of different ML architectures for enhancing the models’ ability to identify subtle spectral signatures associated with different atmospheric processes.



#### Expected Results
  * A set of machine learning models capable of accurately characterizing exoplanet atmospheres using inputs from different observations.
  * Analysis of the models’ performance on observational data, demonstrating their applicability to current and future exoplanet studies.




## Requirements
  * Python
  * PyTorch or TensorFlow (or similar)
  * Background in astronomy is a bonus but not a requirement


<!-- ## Test
Use [this link](https://docs.google.com/document/d/10jZ7aubVkfkcpURQQnvrvbC7o3XgglsJwjS0UA7SRBE/edit?usp=sharing) for instructions on completing the test. -->

## Mentors

* [Katia Matcheva](mailto:ml4-sci@cern.ch) (University of Alabama)
* [Konstantin Matchev](mailto:ml4-sci@cern.ch) (University of Alabama)
* [Sergei Gleyzer](mailto:ml4-sci@cern.ch) (University of Alabama)
* [Jason Terry](mailto:jpterry@uga.edu) (Oxford University)
* [Alex Roman](mailto:ml4-sci@cern.ch) (University of Alabama)
* [Emilie Panek](mailto:ml4-sci@cern.ch) (University of Alabama)

Please **DO NOT** contact mentors directly by email. Instead, please email [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch) with Project Title and **include your CV**. The mentors will then get in touch with you.
