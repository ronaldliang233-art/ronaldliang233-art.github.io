---
title: Solenoid Valve CFD Optimization
permalink: /projects/solenoid-valve/
---

## Overview
This project focuses on improving the internal flow characteristics of a liquid solenoid valve used in automotive applications. 
I conducted CFD-driven design iterations to increase outlet flow rate while balancing manufacturability and geometric complexity.

## Gallery
![Valve geometry](/assets/img/solenoid-valve/geometry.jpg)
![Flow field](/assets/img/solenoid-valve/velocity-contour.jpg)

## Key Design Decisions
- Redesigned internal flow passages to reduce separation and pressure loss.
- Balanced flow improvement against machining feasibility and assembly constraints.
- Evaluated multiple geometries under identical boundary conditions to ensure fair comparison.

## Code Snippet
```python
# Example: post-processing outlet mass flow
import numpy as np

mass_flow = np.mean(outlet_flux)
print(f"Average outlet mass flow: {mass_flow:.3f} kg/s")
