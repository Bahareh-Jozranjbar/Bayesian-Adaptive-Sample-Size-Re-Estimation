# Adaptive Bayesian Sample Size Re-Estimation

## Overview
This repository contains R scripts for visualizing **Adaptive Bayesian Sample Size Re-Estimation**.  
It demonstrates how **variance stabilization** helps in deciding when to stop data collection efficiently.

## Why Use Adaptive Sampling?
Traditional fixed sample sizes often lead to:
- **Too much data** (wasted resources)
- **Too little data** (inconclusive results)

Adaptive sampling dynamically **adjusts the sample size**, ensuring just the right amount of data is collected.

## Plots Generated
| Plot | Description |
|------|------------|
| **plot1_initial_variability.png** | High variability in early data collection |
| **plot2_variance_stabilization.png** | Variance stabilizes as more data is collected |
| **plot3_adaptive_sample_size.png** | Adaptive method sets a stopping threshold |
| **plot4_final_decision.png** | Optimal stopping point is reached |
| **plot5_adaptive_vs_fixed.png** | Comparison of adaptive vs fixed sample sizes |
| **plot6_efficiency.png** | Demonstrates the efficiency of adaptive sampling |

## Running the Code
1. **Install Dependencies**  
   ```r
   install.packages("ggplot2")
   install.packages("dplyr")
   ```


