---
title: Quantum Reinforcement Learning for High Energy Physics
layout: gsoc_proposal
project: QMLHEP
year: 2026
organization:
 - University of Alabama
 - Wisconsin
---

#### Description
The ambitious HL-LHC program will require enormous computing resources and datasets in the next two decades. New technologies are being sought after to replace the present computing infrastructure. A burning question is whether quantum computers can solve the ever growing demand of computing resources in High Energy Physics (HEP) in general and physics at LHC in particular. Our goal here is to explore and to demonstrate that Quantum Reinforcement Learning can be the new paradigm (Proof of Principle).
Discovery of new physics requires the identification of rare signals against immense backgrounds. Development of reinforcement learning (RL) methods will greatly enhance our ability to achieve this objective. However, current RL algorithms require high computing resources on large datasets and excessive computing time to achieve good performance. Quantum Computing, where qubits are used instead of bits in classical computers, has the potential to improve the time complexity or data efficiency of classical algorithms.
With this project we seek to implement Quantum Reinforcement Learning methods for LHC HEP analysis based on the Pennylane framework.

#### Duration
Total project length: 175 hours.

#### Task Ideas
  * Identify the bottlenecks of classical deep RL and propose quantum circuits to efficiently bypass computationally challenging parts of the pipeline.
  * Implement a hybrid or fully quantum deep RL network that may utilize Quanvolutional Neural Networks and a Q-function approximator to minimize the temporal difference error defined by the Bellman equation.
  * Apply the quantum RL method to HEP, benchmarking it against classical state-of-the-art approaches.

#### Expected Results
  * Quantum deep reinforcement learning framework.
  * Applications within HEP data benchmarked against a classical reference model

## Requirements
  * Solid knowledge of machine learning and deep learning
  * Knowledge of quantum mechanics
  * Strong python skills
  * Ability to work independently and proactive on a research project

## Difficulty
Intermediate/Advanced

<!-- ## Test
Use [this link](https://docs.google.com/document/d/1t2cSxEx3vIa6uirfkMkF92rWZM4tTJ_V-lkpYSdukVQ/edit?usp=sharing) for instructions on completing the test. -->

## Mentors
* [Sergei Gleyzer](mailto:ml4-sci@cern.ch) (University of Alabama)
* [Rui Zhang](mailto:ml4-sci@cern.ch) (University of Wisconsin-Madison)
* [Mariia Baidachna](mailto:ml4-sci@cern.ch)

## Links
 * [HL-LHC](https://hilumilhc.web.cern.ch/)
 * [LHC](https://home.cern/science/accelerators/large-hadron-collider)
 * [Pennylane](https://pennylane.ai)
 * [Classical RL for HEP](https://www.frontiersin.org/journals/physics/articles/10.3389/fphy.2022.929064/full)
 * [Quantum RL](https://arxiv.org/abs/2510.14595)

Please **DO NOT** contact mentors directly by email. Instead, please email [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch) with Project Title and **include your CV**. The mentors will then get in touch with you.
