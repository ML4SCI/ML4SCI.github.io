---
title: Agentic AI for Autonomous Gravitational Lensing Simulation Workflows
layout: gsoc_proposal
project: DEEPLENSE
project size: 350hr
year: 2026
organization:
  - Alabama
  - MIT
---

## Description

Strong gravitational lensing is a powerful tool for studying dark matter and the large-scale structure of the universe. Current gravitational lensing simulation pipelines (e.g., [DeepLenseSim](https://github.com/mwt5345/DeepLenseSim) built on Lenstronomy) require substantial manual intervention: researchers must configure parameters, submit cluster jobs, validate outputs, retrain downstream ML models, and iterate on failures. This creates bottlenecks in large-scale dataset generation, limits exploration of parameter space, and consumes researcher time on engineering tasks rather than scientific analysis.
This project proposes the development of an Agentic AI framework to autonomously orchestrate gravitational lensing simulation workflows. Unlike traditional automation scripts that follow rigid rules, agentic systems employ LLM-powered agents that can reason about scientific objectives, adapt to failures, and coordinate complex multi-step workflows with minimal human supervision.


## Duration

Total project length: 175/350 hours.

## Difficulty level

Advanced

## Task ideas
 * Survey agent frameworks and orchestration patterns
 * Design multi-agent system with specialized agents
 * Integrate with DeepLenseSim and SLURM
 * Evaluate automation gains and dataset quality


## Expected results
 * Working multi-agent system for autonomous workflow orchestration
 * Significant reduction in manual intervention with adaptive behavior
 * Benchmark study comparing against traditional pipelines


## Requirements
 * Prior experience with LLMs and local inference tools such as Llama.cpp or Ollama
 * Prior experience with agentic AI frameworks such as Orchestral AI or Pydantic AI 
 * Prior experience with Reinforcement Learning (RL) and its application to AI agents, planning, or autonomous workflow optimization is highly preferred.
 * Familiarity with gravitational lensing is preferred but not mandatory.


## Test
Please use this [link](https://docs.google.com/document/d/10APh49fvayGoSftzO4fGXs2HP3uvYSzG-fSrq4xHL1w/edit?usp=sharing) to access the test for this project.

## Mentors
  * [Michael Toomey](mailto:ml4-sci@cern.ch) (Massachusetts Institute of Technology)
  * [Sergei Gleyzer](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Pranath Reddy](mailto:ml4-sci@cern.ch) (Independent Researcher)
  * [Rajat Shinde](mailto:ml4-sci@cern.ch) (University of Alabama in Huntsville)


Please **DO NOT** contact mentors directly by email. General questions can be directed to [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch). To submit your proposal, CV, and test task solutions, please use [this Google form](https://forms.gle/SPXo8kSwHHptcBmk9).


## Links
  * [Paper 1](https://arxiv.org/abs/2008.12731)
  * [Paper 2](https://arxiv.org/abs/1909.07346)
  * [Paper 3](https://arxiv.org/pdf/2512.15867)
  