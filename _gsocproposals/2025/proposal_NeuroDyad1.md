---
title: CEBRA-Based Data Processing Pipeline for Mapping Time-Locked EEG Paired Sets in Interacting Participants
layout: gsoc_proposal
project: NEURODYAD
year: 2025
organization:
  - Alabama
---

## Description

This project aims to develop a computational pipeline using the Contrastive Embedding for Behavioral and Neural Analysis (CEBRA) method to analyze time-locked EEG data from interacting participants. The goal is to map neural dynamics within dyads, particularly in Speaker-Listener interactions, and to identify parameters that distinguish neurotypical participants from those with clinical diagnoses. The project will use CEBRA algorithm for low-dimensional, interpretable latent embeddings for: 
 * Mapping EEG signals from interacting dyads to uncover neural patterns underlying communication (speaking vs. listening).
 * Exploring differences in feature spaces (e.g., neural synchrony, boundary conditions, or latent manifold properties) that characterize clinical versus neurotypical interactions.
This research is relevant for understanding how neural dynamics in social interaction are shaped by neurotype differences, such as those in Autism Spectrum Disorder (ASD). While CEBRA was originally designed for linking neural and behavioral data, the project aims to adapt it for clinical population comparison in a clinically relevant machine learning application.



## Duration

Total project length: 175/350 hours.

## Task ideas
 * Preprocess EEG recordings and format data to be compatible with CEBRA’s embedding architecture.
 * Implement a pipeline for CEBRA-based mapping of time-locked EEG data from dyads (64-channel EEG).
 * Train the model on neurotypical and clinical dyads, analyzing how latent embeddings encode neural interactions.
 * Identify differentiating features (e.g., variance in manifold structure, neural synchrony, connectivity patterns) that may characterize clinical interactions.

## Test
Please use [this link](https://docs.google.com/document/d/e/2PACX-1vQtRi66DVeoI2tRxT7I6XNi0d_t1JJxDML0dIeUCDMcUqWaG6juTEg25mkQMAKtLyPGQCaq8OM0pz1J/pub) to access the test for this project.

## Requirements
MATLAB, Python; solid understanding of linear algebra, topology, signal processing. Interest in clinical neuroscience and computational methods.

## Expected results
 * A functional pipeline for mapping time-locked EEG hyperscans from interacting participants using CEBRA.
 * Identified neural parameters that differentiate clinical from neurotypical populations.


## Difficulty Level
Intermediate/Advanced


## Mentors
 * Evie Malaia  (University of Alabama)
 * Brendan Ames (University of Southampton, UK)

## Links
 * [CEBRA Pipeline Docs](https://github.com/AdaptiveMotorControlLab/CEBRA)
 * [Paper 1 (Schneider et al., 2023 (CEBRA Paper))](https://arxiv.org/abs/2204.00673)
 * [Paper 2 ](https://arxiv.org/abs/2405.04248)

Please **DO NOT** contact mentors directly by email. Instead, please email [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch) with Project Title and **include your CV** and **test results**. The mentors will then get in touch with you.

