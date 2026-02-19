---
title: Jet Observable Library for Monte Carlo Validation
layout: gsoc_proposal
project: HEPSIM
year: 2026
organization:
  - Alabama
  - Fermilab

---

## Description
Jets are collimated sprays of particles produced abundantly at the [Large Hadron Collider](https://home.cern/science/accelerators/large-hadron-collider). Comparing Monte Carlo generator predictions against data across a comprehensive set of jet observables is essential for validating and tuning simulations. However, the landscape of jet observables — ranging from simple kinematic variables (pT, mass, width) to sophisticated substructure quantities (N-subjettiness, energy correlation functions, Lund jet plane projections) — is large and fragmented across different codebases.
This project aims to build a **unified, well-documented Python/C++ library of jet observables** that can be computed from standard event record formats. The library should provide a single interface to compute a wide catalog of observables, organized by category (IRC-safe, groomed, substructure, event shapes, etc.), and produce standardized output suitable for downstream comparison and plotting. 



## Duration
Total project length: 175/350 hours.

## Task ideas
  * Survey the literature and existing tools (FastJet, EnergyFlow, etc.) to compile a comprehensive catalog of jet observables used in LHC analyses
  * Design a clean, modular Python API where each observable is a callable with standardized input/output
  * Implement core observables: jet kinematic variables, jet shapes, N-subjettiness ratios, energy correlation functions, groomed observables, Lund plane densities, etc
  * Ensure IRC safety annotations and metadata for each observable
  * Write unit tests using known analytic results or reference implementations
  * Provide example notebooks demonstrating usage on public datasets (e.g., from the LHC Olympics or JetClass)
  
  

## Expected results:
  * A pip-installable Python library implementing at least 20–30 jet observables
  * Comprehensive documentation with observable definitions, references, and usage examples
  * Test suite with validation against reference implementations
  * Example notebooks for Monte Carlo validation workflows
  
  

## Difficulty level
Intermediate

## Requirements
  * Python/C++, familiarity with NumPy and scientific computing
  * Some knowledge of jet physics or willingness to learn from the literature
  * Experience with software engineering best practices (testing, documentation, packaging) is a plus
  
  

<!---
## Test
Please use [this link](https://docs.google.com/document/d/10tITU-OJDtaZkLmXpoCpzIM55XcV4Z_7ykS7N9tyISA/edit?usp=sharing) to access the test for this project.
--->

## Mentors
  * [Steve Mrenna](mailto:ml4-sci@cern.ch) (Fermilab)
  * [Konstantin Matchev](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Tony Menzo](mailto:ml4-sci@cern.ch) (University of Alabama + Fermilab)
  * [Ian Pang](mailto:ml4-sci@cern.ch) (Rutgers University)

Please **DO NOT** contact mentors directly by email. Instead, please email [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch) with Project Title and **include your CV** and **test results**. The mentors will then get in touch with you.

## Links
  * [FastJet](https://fastjet.fr/)
  * [EnergyFlow](https://energyflow.network/)
  * [N-subjettiness](https://arxiv.org/abs/1011.2268)
  * [Energy Correlators](https://arxiv.org/abs/2506.09119)
  * [Lund Jet Plane](https://arxiv.org/abs/1807.04758)
  * [Soft Drop](https://arxiv.org/abs/1402.2657)
