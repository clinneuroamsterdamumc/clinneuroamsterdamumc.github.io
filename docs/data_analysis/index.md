---
layout: default
title: Data analysis
nav_order: 3
has_children: true
---
<h1>Data analysis</h1>
This page is dedicated to shared code for data analysis. 

## Timeseries analyses

### Generate Surrogate Data
This code will perform phase randomization on fourier transformed data, consistently across timeseries. This preserves static connectivity and n-lag autocorrelation, but time-dependent connectivity properties are randomized.
[View on GitHub](https://github.com/taabroeders/Recon_Dyn_MS/blob/main/Generate_surrogate.m) 

## Network analyses

### Multilayer Community Detection
This code will perform community detection for multilayer connectivity matrices. The code is relatively computationally inexpensive and uses prior information on subnetwork organization to initialize/constrain the detection.
[View on GitHub](https://github.com/taabroeders/Recon_Dyn_MS/blob/main/CommunityDetection.m)

