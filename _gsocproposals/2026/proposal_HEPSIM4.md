---
title: Agentic Exclusion Limit Extraction
layout: gsoc_proposal
project: HEPSIM
year: 2026
organization:
  - Alabama
  - Fermilab
  - Rutgers

---

## Description
Thousands of BSM searches at the [LHC](https://home.cern/science/accelerators/large-hadron-collider) have produced exclusion limits archived across ATLAS/CMS papers and databases like [SModelS](https://smodels.github.io/). For a theorist proposing a new model, determining what parameter space is already ruled out requires extensive manual literature searches, cross-referencing final states, extracting digitized limit curves, and mapping them onto the model of interest — a tedious, error-prone process that represents a major bottleneck in phenomenological research. This project aims to automate and generalize that approach using agentic programming.
This project builds an **agentic system** within the [HEPTAPOD](https://github.com/tonymenzo/heptapod) framework that automates this process. Given a BSM model specification (particle content, decay channels, production modes), the agent searches the literature and public databases, identifies relevant analyses, extracts applicable bounds, and compiles a structured summary with references and applicability caveats.





## Duration
Total project length: 350 hours.

## Task ideas
  * Survey existing limit databases and formats (HEPData, SModelS, ATLAS/CMS auxiliary material)
  * Implement HEPTAPOD tool modules for querying limit databases, parsing exclusion contours, and matching experimental final states to a user-specified model
  * Build agent workflows that autonomously retrieve and compile limits given a model specification
  * Add validation checks flagging when published analysis assumptions may not apply
  * Test on benchmark models (simplified SUSY, leptoquarks) where the correct relevant limits are known
  * Implement audit trails recording every search query, database hit, and reasoning step
  * Explore whether the agent can identify coverage gaps, parameter regions where no published search applies
  
  
  
  

## Expected results:
  * Working agentic system integrated into HEPTAPOD for automated limit compilation
  * Validation against at least two well-characterized BSM scenarios
  * Transparent audit trail and decision log
  * Open-source code with documentation and examples
  
  
  
  

## Difficulty level
Advanced

## Requirements
  * Strong Python skills, experience with at least one ML/AI framework
  * Familiarity with LLM APIs and tool-use / function-calling paradigms
  * Interest in BSM phenomenology and limit-setting concepts
  * Ability to work independently with significant design freedom
  
  
  
  

<!---
## Test
Please use [this link](https://docs.google.com/document/d/10tITU-OJDtaZkLmXpoCpzIM55XcV4Z_7ykS7N9tyISA/edit?usp=sharing) to access the test for this project.
--->

## Mentors
  * [Steve Mrenna](mailto:ml4-sci@cern.ch) (Fermilab)
  * [Konstantin Matchev](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Alex Roman](mailto:ml4-sci@cern.ch) (University of Alabama)
  * [Tony Menzo](mailto:ml4-sci@cern.ch) (University of Alabama + Fermilab)
  * [Ian Pang](mailto:ml4-sci@cern.ch) (Rutgers University)

Please **DO NOT** contact mentors directly by email. Instead, please email [ml4-sci@cern.ch](mailto:ml4-sci@cern.ch) with Project Title and **include your CV** and **test results**. The mentors will then get in touch with you.

## Links
  * [HEPTAPOD Repository](https://github.com/tonymenzo/heptapod)
  * [HEPTAPOD Paper](https://arxiv.org/abs/2512.15867)
  * [Orchestral AI](https://arxiv.org/abs/2601.02577)
  * [CheckMATE](https://arxiv.org/abs/1312.2591)
  * [GAMBIT](https://arxiv.org/abs/2512.14109)
  * [SModelS](https://smodels.github.io/)
  * [pyhf](https://pyhf.readthedocs.io/en/v0.7.6/)
  