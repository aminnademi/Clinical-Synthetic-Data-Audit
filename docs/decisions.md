# Research Decisions Log

This document records major methodological decisions, alternatives considered, supporting evidence, and the rationale for each decision.

---

## D001 — Use CTGAN, TVAE, and TabDDPM

**Status:** Provisional

**Decision:** Use CTGAN, TVAE, and TabDDPM as the primary synthetic data generators.

**Rationale:**
These three models provide coverage across different generative paradigms and have direct precedent in recent synthetic medical tabular data evaluation literature.

**Evidence:**
Kurakova & Homayouni (2025) evaluate all three models in a medical tabular setting.

---

## D002 — Use clinical plausibility as a separate evaluation dimension

**Status:** Confirmed

**Decision:** Clinical plausibility will not be treated as a simple extension of statistical fidelity.

**Rationale:**
Recent literature shows that statistical similarity does not guarantee clinically valid synthetic records.

---

## D003 — PIMA is currently a pilot dataset

**Status:** Confirmed

**Decision:** PIMA Indians Diabetes is currently used for pipeline development and early experiments, not yet as a final main-study dataset.

**Rationale:**
The dataset has already been used for an initial pilot and is useful for testing reproducibility, preprocessing, generation, and evaluation workflows before committing to the final dataset set.

---
