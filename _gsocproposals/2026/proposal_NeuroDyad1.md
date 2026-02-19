---
title: Brain-to-Brain Decoder - Validating Neural Synchrony Patterns in Human Conversation
layout: gsoc_proposal
project: NEURODYAD
year: 2026
organization:
  - Alabama
---

## Description
When two people talk, their brains synchronize in complex ways. But can we actually decode anything about conversation participants from brain activity? This project uses machine learning on simultaneous brain recordings (hyperscanning EEG) from conversing pairs to rigorously test whether neural patterns generalize across different conversational partners.

## The Challenge
Previous pilot work (Googel Summer of Code 2025, N=8 pairs) achieved 94% accuracy in decoding both conversational roles and participant gender using CEBRA (Contrastive Embedding for Behavioral and Neural Analysis). With our expanded dataset of 40+ pairs, we are looking to build mathematical understanding of which features of neural data inform successful brain-to-brain mapping (explainable AI), and to compare/contrast validation models for topological mapping.

## Why This Matters
Recent research challenges the "deficit model" of social communication differences. Crompton et al. (2025, Nature Human Behaviour) showed that communication breakdowns depend more on neurotype mismatch than individual deficits; but these studies used only behavioral measures. Your work establishes the neural foundation for understanding how brain-to-brain coordination enables (or impairs) communication, with implications for designing assistive technologies.

## Duration
Total project length: 350 hours (12 weeks, full-time).

## Task ideas
  * Implement stratified cross-validation pipeline for dyadic EEG datasets.
  * Compute cross-entropy distance metrics between embedding distributions.
  * Generate learning curves to determine sample size for stable neural dayd decoding.
  * Map embedding features to brain activity, identifying which localization/frequency bands contribute most to neurotype classification.
 

## Test
Please use [this link](https://docs.google.com/document/d/1eW2O4zgUFMa_OM0MspsssCqMIbONZg1pPRmfsMm6H2Y/edit?usp=sharing) to access the test for this project.


## Requirements
**Essential**: Python (NumPy, SciPy), basic signal processing (filtering, FFT)
**Preferred**: Experience with time-series data (including neural), MNE-Python

## Expected results
 * A functional pipeline for mapping time-locked EEG hyperscans from interacting participants using CEBRA.
 * Identified neural parameters that differentiate clinical from neurotypical populations.

## Difficulty Level
Intermediate

## Mentors
 * Evie Malaia (University of Alabama)
 * Brendan Ames (University of Southampton, UK)

## Links
### Key Papers
 * [Project Story So Far](https://medium.com/@mariya.glushanina/extending-cebra-to-dyadic-neural-dynamics-my-google-summer-of-code-journey-5459134af50c)
 * [CEBRA: Schneider et al., Nature 2023](https://arxiv.org/abs/2204.00673)
 * [Our Dyadic Work](https://arxiv.org/abs/2509.23479v1)
 * [Communication Theory: Crompton et al., 2025 ](https://www.nature.com/articles/s41562-025-02163-z)
 * [Cross-Entropy Test: Roca et al., 2023](https://linkinghub.elsevier.com/retrieve/pii/S2667237522002958)
 ### Tools and Resources
 * [CEBRA Documentation](https://github.com/AdaptiveMotorControlLab/CEBRA)
 * [MNE-Python Tutorials](https://mne.tools/stable/auto_tutorials/index.html)

Please **DO NOT** contact mentors directly by email. Instead, please email [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch) with Project Title and **include your CV** and **test results**. The mentors will then get in touch with you.

