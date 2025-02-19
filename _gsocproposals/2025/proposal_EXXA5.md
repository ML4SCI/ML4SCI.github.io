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

Advancing the understanding of exoplanets and planet formation requires a wide variety of observational methods and data modalities. Planet formation is a complex process that involves the assembly of a planet from a protoplanetary disk, an environment that instruments have only recently been able to resolve. These observations rely mostly on image data, including line emission and continuum data. The analysis of this data is a complex process, but, when done successfully, it opens new avenues for understanding planet formation, the resulting systems of exoplanets, and the potential of these systems for habitability. A complementary route is to use data from the atmospheres of exoplanets. The characterization of exoplanet atmospheres is crucial for understanding their compositions, weather patterns, and potential habitability. This project aims to develop a foundation machine learning models that will analyze data of different environments from different instruments to further our understanding of planet formation, extoplanet systems, exoplanet properties, and, ultimately, the potential of these systems for habitability. The models will use image data of disks, spectral data from exoplanets, identifying forming exoplanets, processes and substructures that are important in protoplanetary disk evolution, chemical abundances in exoplanet atmosphers, cloud/haze structure, and different atmospheric processes. The project will leverage data from telescopes and space missions, along with simulations of protoplanetary disks and exoplanetary atmospheres under various conditions, to train and validate the models.

#### Duration

Total project length: 175/350 hours.

#### Task Ideas
  * Assemble a consolidated database using existing protoplanetary disk and exoplanet transit observations from different instruments, spectral resolutions, and spectral ranges from publicly available archives. 
  * Develop an ML approach to overcome the specific instrumental differences for the different observations. Training can be done on existing synthetic databases simulating the instrument performance (Hubble Space Telescope, JWST, ALMA, Ariel etc.)
  * Apply the trained models to real observational data from Hubble, JWST, ALMA, and future telescopes to characterize protoplanetary disks and exoplanet atmospheres.
  * Explore the use of different ML architectures for enhancing the models’ ability to identify subtle signatures in the different data modalities associated with important physical properties and processes that may influence the formation and identification of habitable systems.



#### Expected Results
  * A set of machine learning models capable of accurately characterizing protoplanetary disks and exoplanet atmospheres using inputs from different observations.
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
