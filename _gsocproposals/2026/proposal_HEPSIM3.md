---
title: ML-Based Simulation Bias Analysis - Pythia vs Herwig vs Data
layout: gsoc_proposal
project: HEPSIM
year: 2026
organization:
  - Alabama
  - Fermilab
  - Rutgers

---

## Description
Different Monte Carlo event generators, most notably [Pythia](https://pythia.org/) and [Herwig](https://herwig.hepforge.org/), employ distinct physics models for parton showering, hadronization, and the underlying event. These modeling choices lead to systematic differences in predicted distributions that directly impact physics measurements and searches for new phenomena at the [LHC](https://home.cern/science/accelerators/large-hadron-collider). Quantifying these inter-generator biases, and their discrepancies with data, is crucial for assigning robust systematic uncertainties.
This project applies **machine learning classifiers** to perform a systematic, high-dimensional comparison of Pythia, Herwig, and (where available) unfolded experimental data. Rather than examining observables one at a time, ML classifiers can detect subtle multi-dimensional correlations that distinguish generators. The classifier output itself, and the features driving its decisions, reveal which regions of phase space carry the largest modeling uncertainties.
The student will train classifiers (boosted decision trees, neural networks, or similar) to discriminate between generator samples and/or data, then extract interpretable information about the nature and location of biases using techniques such as SHAP values, feature importance, and learned reweighting.




## Duration
Total project length: 175/350 hours.

## Task ideas
  * Prepare matched Pythia and Herwig samples for standard LHC processes (e.g., Z+jets, tt̄, dijet)
  * Compute a comprehensive set of observables using the jet observable library (HEPSIM2) or equivalent
  * Train binary classifiers (BDT, neural network) to discriminate Pythia vs Herwig events
  * Extract feature importances and SHAP values to identify which observables and phase-space regions drive the largest inter-generator differences
  * Where public unfolded data is available, extend the analysis to MC-vs-data comparison
  * Explore the use of the classifier output as a learned reweighting function and compare with the symbolic regression approach (HEPSIM1)
  * Quantify the resulting uncertainty envelopes for key distributions
  
  
  

## Expected results:
  * Trained ML classifiers that quantify Pythia–Herwig and MC–data discrepancies
  * Interpretability analysis (SHAP, feature importance) identifying the leading sources of simulation bias
  * Comparison of ML-derived bias estimates with traditional uncertainty prescriptions
  * Open-source code and documentation
  
  
  

## Difficulty level
Intermediate/Advanced

## Requirements
  * Python, PyTorch or TensorFlow, scikit-learn
  * Experience with ML classification and interpretability techniques
  * Some familiarity with HEP simulation tools or willingness to learn
  * Ability to work independently on a research project
  
  
## Test
Please use [this link](https://alabama.box.com/s/blfka5vq4g9mkxm5l0uuzozv2erslc52) to access the test for this project.


## Mentors
  * [Steve Mrenna](mailto:ml4-sci@cern.ch) (Fermilab)
  * [Konstantin Matchev](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Tony Menzo](mailto:ml4-sci@cern.ch) (University of Alabama + Fermilab)
  * [Ian Pang](mailto:ml4-sci@cern.ch) (Rutgers University)

Please **DO NOT** contact mentors directly by email. General questions can be directed to [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch). To submit your proposal, CV, and test task solutions, please use [this Google form](https://forms.gle/SPXo8kSwHHptcBmk9).

## Links
  * [Pythia 8](https://pythia.org/)
  * [Herwig 7](https://herwig.hepforge.org/)
  * [SHAP Values](https://arxiv.org/abs/1705.07874)
  * [Classifier-based reweighting](https://arxiv.org/abs/2007.11586)
  * [The Pareto frontier of resilient jet tagging](https://arxiv.org/pdf/2509.19431)
