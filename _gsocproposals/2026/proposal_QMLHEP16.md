---
title: Quantum Circuit Design with LLMs
layout: gsoc_proposal
project: QMLHEP
year: 2026
organization:
 - University of Alabama
---

#### Note
This project is a collaboration with EXXA and QMLHEP.

#### Description

Variational quantum circuits (VQCs) lie at the core of many near-term quantum algorithms, enabling hybrid quantum–classical optimization of parametrized quantum circuits. Efficient VQC architectures underpin applications such as quantum machine learning (QML) and variational eigensolvers. However, the design of VQC architectures remains a largely heuristic and problem-dependent process that often involves extensive trial and error. VQCs are also very unintuitive for human designers, as quantum phenomena such as entanglement and interference have no classical analogs. As circuit depth and the number of qubits increase, the combinatorial circuit space rapidly becomes intractable for manual exploration, motivating new forms of automation.
By leveraging the reasoning capabilities of Large Language Models (LLMs), this project aims to automate the synthesis and optimization of quantum circuits. Beyond initial design, the project implements an iterative "closed-loop" testing framework where the LLM interacts with quantum simulators and hardware backends to debug circuits, minimize gate depth, and verify logical equivalence. This approach seeks to bypass the "bottleneck" of manual circuit transpilation, potentially uncovering novel gate sequences that human intuition might overlook.



#### Duration

Total project length: 175/350 hours.

#### Task Ideas
  * Identify the bottlenecks of the existing quantum circuit design process.
  * Identify the features which make a quantum circuit useful (potentially having a quantum advantage).
  * Set up a flexible structure for exploring hybrid classical-quantum algorithms.
  * Create an agentic framework that automatically creates, tests and evaluates quantum circuits.


#### Expected Results
  * Agentic framework for quantum circuit design, testing and evaluation.


## Requirements
  * Solid knowledge of machine learning and deep learning
  * Knowledge of quantum mechanics
  * Strong python skills
  * Ability to work independently and proactive on a research project

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
  * [Orchestral AI: A Framework for Agent Orchestration](https://arxiv.org/abs/2601.02577)
  * [Qiboml: towards the orchestration of quantum-classical machine learning](https://arxiv.org/abs/2510.11773)
  * [AI Agents for Variational Quantum Circuit Design](https://arxiv.org/abs/2602.19387)
  
Please **DO NOT** contact mentors directly by email. Instead, please email [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch) with Project Title and **include your CV**. The mentors will then get in touch with you.
