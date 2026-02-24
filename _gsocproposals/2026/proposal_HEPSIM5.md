---
title: Agentic Lagrangian Extraction from the Literature
layout: gsoc_proposal
project: HEPSIM
year: 2026
organization:
  - Alabama
  - Fermilab
  - Rutgers

---

## Description
Hundreds of BSM Lagrangians have been proposed in the literature (extended Higgs sectors, leptoquarks, SUSY variants, dark matter portals, EFT extensions at various operator dimensions). When a researcher wants to simulate a particular scenario, they must locate the Lagrangian in the literature, translate it into a [FeynRules](https://feynrules.irmp.ucl.ac.be/) model file, and validate the implementation. This literature-to-simulation pipeline is a significant manual bottleneck.
This project builds an **agentic system** within the [HEPTAPOD](https://feynrules.irmp.ucl.ac.be/) framework that automates this workflow. Given a BSM scenario description, the agent searches the literature, identifies the relevant Lagrangian and conventions, generates a syntactically correct FeynRules `.fr` model file, and validates it, checking particle content, symmetry properties, and where possible reproducing known cross sections or decay widths using HEPTAPOD's existing FeynRulesToUFOTool and downstream event generation tools.


## Duration
Total project length: 350 hours.

## Task ideas
  * Survey publicly available FeynRules model files (model database, HEPTAPOD examples) to catalog conventions and patterns
  * Implement HEPTAPOD tool modules for searching the HEP literature (INSPIRE, arXiv), extracting Lagrangian terms, and generating FeynRules .fr files
  * Build agent workflows that go from a scenario description to a validated model file, using HEPTAPOD's existing tools for UFO compilation and event generation
  * Implement validation: particle spectrum consistency, gauge invariance, reproduction of known decay widths or cross sections where available
  * Test against benchmark models already in the FeynRules database (scalar leptoquarks, 2HDM, simplified dark matter)
  * Implement audit trail recording literature sources, extracted terms, and model-building decisions
  

## Expected results:
  * Working agentic system integrated into HEPTAPOD for Lagrangian extraction and model file generation
  * Validation against at least two models with known FeynRules implementations
  * Audit trail documenting the agent's reasoning from literature to model file
  * Open-source code with examples


## Difficulty level
Advanced

## Requirements
  * Strong Python skills, experience with AI/ML frameworks
  * Familiarity with LLM tool-use and agentic programming patterns
  * Interest in particle physics theory (Lagrangians, EFT, BSM), coursework or reading a plus
  * Exposure to Mathematica or FeynRules helpful
  * Ability to work independently on an open-ended research project


## Test
Please use [this link](https://alabama.box.com/s/blfka5vq4g9mkxm5l0uuzozv2erslc52) to access the test for this project.


## Mentors
  * [Steve Mrenna](mailto:ml4-sci@cern.ch) (Fermilab)
  * [Konstantin Matchev](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Alex Roman](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Tony Menzo](mailto:ml4-sci@cern.ch) (University of Alabama + Fermilab)
  * [Ian Pang](mailto:ml4-sci@cern.ch) (Rutgers University)

Please **DO NOT** contact mentors directly by email. General questions can be directed to [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch). To submit your solutions, please use [this Google form](https://forms.gle/SPXo8kSwHHptcBmk9).

## Links
  * [HEPTAPOD Repository](https://github.com/tonymenzo/heptapod)
  * [HEPTAPOD Paper](https://arxiv.org/abs/2512.15867)
  * [Orchestral AI](https://arxiv.org/abs/2601.02577)
  * [The Denario project: Deep knowledge AI agents for scientific discovery](https://arxiv.org/abs/2510.26887)
  * [FeynRules](https://feynrules.irmp.ucl.ac.be/)
  * [FeynRules Model Database](https://feynrules.irmp.ucl.ac.be/wiki/ModelDatabaseMainPage)
  * [INSPIRE](https://inspirehep.net/)