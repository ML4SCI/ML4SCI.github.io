---
title: Quantum Resource Analysis and Benchmarking 
layout: gsoc_proposal
project: QMLHEP
year: 2026
organization:
 - University of Alabama
---

#### Note
This project is a collaboration with EXXA and QMLHEP.

#### Description

This project aims to bridge the gap between abstract quantum resource theories and practical circuit design by developing a unified computational library for quantifying "quantumness." It will systematically compile and implement diverse measures of quantum resources (including Entanglement Entropy, Magic (via Stabilizer Rényi Entropy), Mana (for qudit systems), and Bell-type Nonlocality) into a single, high-performance software framework. By providing a standardized toolset, the project will enable researchers to precisely profile the "resource cost" of a quantum state or circuit, moving beyond simple gate counts to a more nuanced understanding of the fundamental properties that drive quantum advantage and classical non-simulability.
Building upon this computational foundation, the project will conduct an extensive exploration into how these resources interact and evolve within various quantum circuit architectures. We will analyze the trade-offs between different resources and utilize our code to identify the specific thresholds where a circuit's resource profile makes it advantageous. The final stage of the project will involve a large-scale benchmarking study, using our software to correlate resource levels with the performance and success rates of standard algorithms (like QAOA or QPE), ultimately establishing a "resource-driven" methodology for optimizing the next generation of quantum hardware.


#### Duration

Total project length: 175/350 hours.

#### Task Ideas
  * Compile a list of the standard measures of quantum resources.
  * Create a library for their efficient calculation. 
  * Set up a flexible structure for exploring hybrid classical-quantum algorithms.
  * Perform a large-scale benchmark study of resource levels in standard algorithms.


#### Expected Results
  * A library for computing and benchmarking quantum resources in quantum algorithms.


## Requirements
  * Solid knowledge of machine learning and deep learning
  * Knowledge of quantum mechanics
  * Strong python skills
  * Ability to work independently and be proactive on a research project

## Difficulty
Intermediate/Advanced

## Test
Use [this link](https://alabama.box.com/s/hhtuposm1m46ra8krmwn95n9l2iaj5l5) for instructions on completing the test.

## Mentors

* [Katia Matcheva](mailto:ml4-sci@cern.ch) (University of Alabama)
* [Konstantin Matchev](mailto:ml4-sci@cern.ch) (University of Alabama)
* [Sergei Gleyzer](mailto:ml4-sci@cern.ch) (University of Alabama)
* [Alex Roman](mailto:ml4-sci@cern.ch) (University of Alabama)
* [Marco Knipfer](mailto:ml4-sci@cern.ch) (University of Alabama)

## Links
  * [PennyLane](https://pennylane.ai)
  * [Maximal magic for two qubit states](https://arxiv.org/abs/2502.17550)
  * [Unsupervised Beyond-Standard-Model Event Discovery at the LHC with a Novel Quantum Autoencoder](https://arxiv.org/abs/2407.07961)
  * [AI Agents for Variational Quantum Circuit Design](https://arxiv.org/abs/2602.19387)

Please **DO NOT** contact mentors directly by email. General questions can be directed to [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch). To submit your proposal, CV, and test task solutions, please use [this Google form](https://forms.gle/SPXo8kSwHHptcBmk9).
