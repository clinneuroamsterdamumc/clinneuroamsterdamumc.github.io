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

### Generate Surrogate Data (matlab){: .label }
This code will perform phase randomization on fourier transformed data, consistently across timeseries. This preserves static connectivity and n-lag autocorrelation, but time-dependent connectivity properties are randomized.

[Code](https://github.com/taabroeders/Recon_Dyn_MS/blob/main/Generate_surrogate.m){: .btn }

Please use the following citation if you are using this code:
- PAPER TOMMY

## Network analyses

### Multilayer Community Detection
This code will perform community detection for multilayer connectivity matrices. The code is relatively computationally inexpensive and uses prior information on subnetwork organization to initialize/constrain the detection.

[Code](https://github.com/taabroeders/Recon_Dyn_MS/blob/main/CommunityDetection.m){: .btn }

Please use the following citation if you are using this code:
- PAPER TOMMY

