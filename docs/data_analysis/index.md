---
layout: default
title: Data analyses
nav_order: 3
has_children: true
---
<h1>Data analyses</h1>
This page is dedicated to shared code for data analyses. 

## Timeseries analyses

### Generate Surrogate Data
This code will perform phase randomization on fourier transformed data, consistently across timeseries. This preserves static connectivity and n-lag autocorrelation, but time-dependent connectivity properties are randomized.
[Code](https://github.com/taabroeders/Recon_Dyn_MS/blob/main/Generate_surrogate.m){: .btn }

Please cite the following paper if you are using this code:
- PAPER TOMMY

## Network analyses

### Multilayer Community Detection
This code will perform community detection for multilayer connectivity matrices. The code is relatively computationally inexpensive and uses prior information on subnetwork organization to initialize/constrain the detection.
[Code](https://github.com/taabroeders/Recon_Dyn_MS/blob/main/CommunityDetection.m){: .btn }

Please cite the following paper if you are using this code:
- PAPER TOMMY

