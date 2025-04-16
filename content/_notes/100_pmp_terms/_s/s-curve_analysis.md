---
title: S-Curve Analysis
draft: false
date: 2025-04-14
tags:
  - performance-measurement
  - cost-management
  - schedule-management
  - earned-value-management
---

**S-Curve Analysis** is a technique used to indicate performance trends by using a graph that displays cumulative costs over a specific time period.

It visually compares planned value (PV), earned value (EV), and actual cost (AC) across the project timeline, allowing project managers to assess cost and schedule performance, detect variances, and forecast future outcomes.

## Key Characteristics

- **Graphical Representation** – Displays time-based cumulative values in an S-shaped curve  
- **Tracks Performance** – Plots PV, EV, and AC to visualize deviations  
- **Supports Earned Value Management** – Aligns with EVM metrics for integrated control  
- **Useful for Forecasting** – Projects future trends based on current performance  

## Example Scenarios

- Identifying a schedule delay by comparing EV to PV on the curve  
- Detecting cost overruns when AC rises faster than EV  
- Using the curve to forecast total project duration or cost at completion  

## S-Curve analysis shown in Python

<div style="text-align: center;">
  <img src="https://www.dropbox.com/scl/fi/26g50kxtnbc707jc8r6ga/s-curve.png?rlkey=piyeiwldoiaip32x6e9mxlw95&st=gwzmxbhz&raw=1" alt="S-Curve Analysis" style="max-width: 100%; height: auto;" />
</div>

<details>
<summary>Click to expand S-Curve Analysis code</summary>

```python
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd

# Simulate data for S-curve analysis
days = np.arange(0, 101, 5)
planned = 0.8 * days + 2 * np.sin(0.1 * days)  # Simulated planned value
actual = 0.75 * days + 2 * np.sin(0.1 * days + 1)  # Simulated actual value
earned = 0.7 * days + 2 * np.sin(0.1 * days + 0.5)  # Simulated earned value

# Plot
plt.figure(figsize=(10, 6))
plt.plot(days, planned, label='Planned Value (PV)', linewidth=2)
plt.plot(days, actual, label='Actual Cost (AC)', linewidth=2)
plt.plot(days, earned, label='Earned Value (EV)', linewidth=2)

plt.title("S-Curve Analysis")
plt.xlabel("Time (days)")
plt.ylabel("Cumulative Cost")
plt.grid(True)
plt.legend()
plt.tight_layout()

# Show the plot
plt.show()
```
</details>

## Role in Performance Monitoring

- **Improves Stakeholder Communication** – Offers a visual summary of project health  
- **Enables Trend Analysis** – Helps predict potential overruns or underruns  
- **Supports Decision-Making** – Informs corrective actions based on visual evidence  
- **Aligns With Control Metrics** – Complements SPI, CPI, and variance analyses  

See also: [[Earned Value (EV)]], [[Planned Value (PV)]], [[Actual Cost (AC)]], [[Schedule Performance Index (SPI)]], [[Cost Performance Index (CPI)]].
