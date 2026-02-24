---
title: Deriving planetary surface composition from orbiting observations from spacecraft
layout: gsoc_proposal
project: Lunar Prospector
year: 2023
organization:
 - Alabama
 - Goddard
 - JHUAPL
---

## Description

NASA has sent many robotic spacecraft to perform remote-sensing observations of surface composition from orbit. This includes gamma-ray observations of planetary surfaces, which provide position-dependent energy spectra whose shape is due to the sum of components from different elements. We seek to develop a machine learning (ML) approach to isolate the element-dependent contributions to the measurements as a function of surface location. We will use the Lunar Prospector Gamma-Ray Spectrometer dataset to train a model using the moon as the training dataset. The first objective is to identify the best ML model approach and quantify its accuracy as this data, and the Moon, are well understood. We will then use domain adaptation to extend the approach to other planetary objects that are less well known, enabling new discoveries.


## Duration

Total project length: 175/350 hours.

## Task ideas
  * Identify the best ML model to extract element composition information from cumulative gamma-ray spectra using Lunar Prospector measurements of the Moon.
  * Use domain adaptation to extend the model to other planetary surfaces.

## Expected results
  * Identification of a suitable model with a proof-of-concept using Lunar Prospector data.


<!-- ## Test
Please use [this link](https://ml4sci.org/assets/GSOC_2023_Evaluation_Test.pdf) to access the test for this project. -->

## Requirements 
Python and relevant past experience in Machine Learning.




## Mentors

  * [Patrick Peplowski](mailto:ml4-sci@cern.ch) (JHUAPL)
  * [Sergei Gleyzer](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Mauricio Allyon-Unzueta](mailto:ml4-sci@cern.ch) (NASA Goddard)

 
Please **DO NOT** contact mentors directly by email. General questions can be directed to [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch). To submit your solutions, please use [this Google form](https://forms.gle/SPXo8kSwHHptcBmk9).

## Links
  * [Paper 1](https://agupubs.onlinelibrary.wiley.com/doi/pdfdirect/10.1029/2005JE002656)
