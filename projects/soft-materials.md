---
title: Soft Materials Simulation Research
permalink: /projects/soft-materials/
---

## Overview
This page summarizes my ongoing simulation-focused exploration in soft materials, with an emphasis on connecting modeling choices to physical intuition and experimental relevance.

## Focus Areas
- Constitutive modeling and parameter sensitivity
- Deformation, stability, and boundary-condition effects
- Model validation mindset: what can/can’t be trusted from simulation alone

## Representative Work
### Study 1 — (Add a short title)
- **Goal:** (1 sentence)
- **Method:** (FEA / custom numerical model / etc.)
- **Key takeaway:** (1 sentence)

### Study 2 — (Add a short title)
- **Goal:** …
- **Method:** …
- **Key takeaway:** …

## Code / Workflow Snippet
```python
# Example: parameter sweep skeleton
for E in E_list:
    for nu in nu_list:
        run_simulation(E=E, nu=nu)
