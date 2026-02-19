---
title: Symbolic Regression for Observable Event-Level Reweighting
layout: gsoc_proposal
project: HEPSIM
year: 2026
organization:
  - Alabama
  - Fermilab
  - Rutgers
  - Kansas

---

## Description
Monte Carlo event generators such as Pythia and Herwig are indispensable tools in high-energy physics, but their predictions do not perfectly reproduce experimental data. A common strategy is to apply event-level reweighting: assigning each simulated event a weight so that the reweighted simulation better matches observed distributions. Currently, these weights are often derived from binned ratios in only one or two observables, which can miss important correlations.
This project aims to use symbolic regression to discover closed-form, interpretable reweighting functions that operate on event-level features (jet multiplicities, kinematic variables, angular correlations, etc.). Unlike black-box ML reweighting, symbolic regression returns human-readable mathematical expressions, enabling physicists to understand why certain regions of phase space require correction and potentially revealing deficiencies in the underlying physics modeling.
The student will implement a symbolic regression pipeline (using frameworks such as [PySR](https://github.com/MilesCranmer/PySR), [gplearn](https://gplearn.readthedocs.io/en/latest/), or equivalent) that ingests Monte Carlo truth-level event data alongside reference distributions (from higher-order calculations or unfolded data) and outputs analytic reweighting formulae. The pipeline should support configurable complexity penalties, dimensional analysis constraints, and validation through closure tests.


## Duration
Total project length: 175/350 hours.

## Task ideas
  * Survey existing symbolic regression frameworks and select/adapt one suitable for HEP event data
  *	Design an input feature set from standard event-level observables (jet pT, η, φ, multiplicity, HT, missing ET, event shapes, etc.)
  *	Train symbolic regression models to learn reweighting functions from MC-to-data (or MC-to-MC) ratios
  *	Implement dimensional analysis and physics-informed constraints to guide the search toward physically meaningful expressions
  *	Validate discovered expressions through closure tests on held-out data and comparison to binned reweighting baselines
  *	Package the pipeline as a reusable Python tool with clear documentation
  

## Expected results:
  * A working symbolic regression pipeline for event-level reweighting in HEP
  *	A set of benchmark reweighting expressions on at least one standard MC dataset (e.g., Z+jets or tt̄)
  *	Documentation and comparison against traditional binned reweighting methods
  *	Open-source code repository with examples and tutorials
  

## Difficulty level
Intermediate

## Requirements
  * Python, familiarity with NumPy/SciPy and at least one ML framework (PyTorch or TensorFlow)
  * Basic understanding of symbolic regression or genetic programming concepts
  * Some familiarity with HEP event data formats (ROOT, HepMC, or similar) is helpful but not required
  * Ability to work independently on a research project
  

<!---
## Test
Please use [this link](https://docs.google.com/document/d/10tITU-OJDtaZkLmXpoCpzIM55XcV4Z_7ykS7N9tyISA/edit?usp=sharing) to access the test for this project.
--->

## Mentors
  * [Steve Mrenna](mailto:ml4-sci@cern.ch) (Fermilab)
  * [Konstantin Matchev](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Katia Matcheva](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Kyoungchul Kong](mailto:ml4-sci@cern.ch) (University of Kansas)
  * [Tony Menzo](mailto:ml4-sci@cern.ch) (University of Alabama + Fermilab)
  * [Ian Pang](mailto:ml4-sci@cern.ch) (Rutgers University)

Please **DO NOT** contact mentors directly by email. Instead, please email [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch) with Project Title and **include your CV** and **test results**. The mentors will then get in touch with you.

## Links
  * [PySR: Symbolic Regression in Python](https://github.com/MilesCranmer/PySR)
  * [Is the machine smarter than the theorist: Deriving formulas for particle kinematics with symbolic regression](https://inspirehep.net/literature/2182388)
  * [Pythia 8](https://pythia.org/)
  * [Herwig 7](https://herwig.hepforge.org/)
