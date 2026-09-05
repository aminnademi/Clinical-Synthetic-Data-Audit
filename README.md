# Synthetic Medical Tabular Data Evaluation

## Overview

This research project investigates the quality and clinical plausibility of synthetic medical tabular data generated using:

* CTGAN
* TVAE
* TabDDPM

The project focuses on three complementary dimensions:

1. Statistical Fidelity
2. Clinical Plausibility
3. Downstream Utility

A central research question is whether a hybrid rule-based + LLM-based clinical evaluator can identify clinically implausible synthetic records beyond conventional rule-based checks, and how filtering based on clinical plausibility affects statistical fidelity and downstream utility.

## Core Research Questions

### RQ1

How do CTGAN, TVAE, and TabDDPM differ in statistical fidelity and clinical plausibility across medical tabular datasets?

### RQ2

Does an LLM-based evaluator identify clinically implausible records that conventional rule-based checks fail to identify?

### RQ3

Does combining rule-based and LLM-based evaluation provide additional value over rule-based evaluation alone?

### RQ4

How does clinical filtering affect statistical fidelity and downstream utility (TSTR)?

## Current Dataset Status

PIMA Indians Diabetes is currently being used as a pilot/development dataset.

It is NOT yet considered the final dataset for the main study.

Additional datasets will be evaluated before the final experimental design is frozen.

## Current Research Backbone

The current core literature includes:

* Kurakova & Homayouni (2025)
* Hahn et al. (2026)
* Masud & Hasan (2026)
* Pilgram et al. (2025)
* Nanevski et al. (2026)

These papers motivate the multidimensional evaluation framework, clinical constraints, clinical filtering, hallucination analysis, and downstream utility considerations.

## Project Principle

The researchers remain responsible for scientific decisions, experimental design, interpretation, and final claims.

AI tools may be used for:

* literature discovery and comparison
* coding assistance
* debugging
* experimental critique
* writing and editing assistance

AI-generated outputs are treated as assistance, not ground truth.