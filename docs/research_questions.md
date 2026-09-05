# Research Questions

## Main Research Question

Can a hybrid rule-based + LLM-based evaluator identify clinically implausible records in synthetic medical tabular data beyond conventional rule-based checks, and how does filtering based on this evaluation affect statistical fidelity and downstream utility?

## Research Questions

### RQ1 — Synthetic Data Quality

How do CTGAN, TVAE, and TabDDPM differ in statistical fidelity and clinical plausibility across medical tabular datasets?

### RQ2 — Incremental Value of LLM Evaluation

Does an LLM-based evaluator identify clinically implausible synthetic records that are not detected by conventional rule-based checks?

### RQ3 — Hybrid Evaluation

Does combining rule-based and LLM-based evaluation improve clinical plausibility assessment compared with rule-based evaluation alone?

### RQ4 — Filtering and Utility

How does filtering synthetic records according to clinical plausibility affect statistical fidelity and downstream utility measured using TSTR?

## Preliminary Hypotheses

### H1

Different synthetic data generators will exhibit different patterns of statistical fidelity and clinical plausibility.

### H2

Rule-based and LLM-based evaluators will not produce completely overlapping decisions.

### H3

A validated hybrid evaluator will detect clinically implausible records that are missed by rule-based evaluation alone.

### H4

Improving clinical plausibility through filtering will not necessarily improve downstream utility, and the effect may depend on the generator and dataset.

These are hypotheses to be tested, not assumptions about the final results.

## Important Scope Boundaries

The project does not currently aim to:

* develop a new synthetic data generator
* benchmark a large number of generators
* perform a broad privacy study
* optimize dozens of evaluation metrics
* compare many different LLMs
* fine-tune an LLM
* reproduce a large-scale benchmark study

The primary contribution is the evaluation of a hybrid clinical plausibility assessment approach and its relationship with statistical fidelity and downstream utility.
