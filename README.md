<div align="center">

# Phase 2-2 — Parameter Adjustment Recommendation

### ICU Mechanical Ventilator Parameter Adjustment Recommendation Based on Multivariate Time-Series Analysis

<br>

A deep learning approach for recommending mechanical ventilator parameter adjustments using multivariate ventilator time-series data.

<br>

[← Main Research Repository](https://github.com/hiimsharon/icu-ventilator-adjustment)

<br>

[Overview](#overview) ·
[Research Objective](#research-objective) ·
[Methodology](#methodology) ·
[Repository Structure](#repository-structure) ·
[Research Status](#research-status)

</div>

---

## Overview

Phase 2-2 represents the third decision stage of the proposed ICU mechanical ventilator adjustment framework.

This phase focuses on recommending appropriate ventilator parameter adjustments based on multivariate ventilator-related time-series information.

The task is formulated as a parameter prediction task to determine suitable ventilator setting adjustments after the adjustment direction has been identified.

---

## Research Objective

| Item | Description |
|---|---|
| Clinical Task | Ventilator parameter adjustment recommendation |
| Learning Task | Regression |
| Input Data | Multivariate ventilator time-series data |
| Sequence Models | Long Short-Term Memory (LSTM) and Gated Recurrent Unit (GRU) |
| Hyperparameter Optimization | Bayesian Optimization with Tree-structured Parzen Estimator |
| Output | Recommended ventilator parameter adjustments |

---

## Methodology

### Data Preparation

Multivariate ventilator records are processed into sequential samples according to the temporal characteristics of ICU ventilator management.

---

### Model Development

Deep learning sequence models, including LSTM and GRU, are developed to learn temporal patterns associated with ventilator adjustment decisions.

---

### Hyperparameter Optimization

Bayesian optimization based on the Tree-structured Parzen Estimator is applied to search suitable model configurations.

---

### Model Evaluation

Model performance is evaluated using regression metrics to assess the predictive performance of the parameter adjustment recommendation task.

---

## Repository Structure

```text
icu-ventilator-phase-2-2
|
├── README.md
├── assets/
└── documents/
```

---

## Research Status

Completed research phase.

The complete research workflow and final public materials will be updated according to research release planning.

---

## Notice

Clinical source data and patient-level information are not publicly distributed.

The materials provided in this repository are intended for academic reference and research communication only.

---

<div align="center">

<sub>

Copyright © 2026 Sha Huang. All Rights Reserved.

</sub>

</div>
