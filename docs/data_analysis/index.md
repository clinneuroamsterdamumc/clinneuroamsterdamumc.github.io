---
layout: default
title: Data analyses
nav_order: 4
has_children: false
has_toc: false
---
# Data analyses

This page is dedicated to shared code for data analyses. Code is categorized by type of analysis. Please use the corresponding citations if you are using code from this page. 

## Timeseries analyses

### Generate Surrogate Data
This code will perform phase randomization on fourier transformed data, consistently across timeseries. This preserves static connectivity and n-lag autocorrelation, but time-dependent connectivity properties are randomized. [Go to code](https://github.com/taabroeders/Recon_Dyn_MS/blob/main/Generate_surrogate.m)

Please use the following citation if you are using this code:
- Broeders, T. A., Douw, L., Eijlers, A. J., Dekker, I., Uitdehaag, B. M., Barkhof, F., ... & Schoonheim, M. M. (2022). A more unstable resting-state functional network in cognitively declining multiple sclerosis. Brain Communications, 4(2), fcac095.

## Network analyses

### Multilayer Community Detection
This code will perform community detection for multilayer connectivity matrices. The code is relatively computationally inexpensive and uses prior information on subnetwork organization to initialize/constrain the detection. [Go to code](https://github.com/taabroeders/Recon_Dyn_MS/blob/main/CommunityDetection.m)

Please use the following citation if you are using this code:
- Broeders, T. A., Douw, L., Eijlers, A. J., Dekker, I., Uitdehaag, B. M., Barkhof, F., ... & Schoonheim, M. M. (2022). A more unstable resting-state functional network in cognitively declining multiple sclerosis. Brain Communications, 4(2), fcac095.

