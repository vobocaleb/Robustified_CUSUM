# Robustified CUSUM for Anomaly Detection in Heteroscedastic Streaming Environments

## Overview
This repository contains the code and results for the paper:
**"Robustified CUSUM for Anomaly Detection in Heteroscedastic Streaming Environments"**
accepted at ICCIS 2026.

## What this project does
- Implements a robustified CUSUM method for anomaly detection
- Uses recursive M-estimators for location and scale
- Adapts to changing variance in real time
- Compares performance with standard CUSUM

## Simulation Scenarios
- Scenario 1: No variance Change: This scenario was not considered 
- Scenario 2: Step variance change + mean shift
- Scenario 3: Festival spike (UPI-like)
- Scenario 4: Pure variance change (no mean shift)

## Results
- Detection rates: 51.8% – 100%
- Average delays: 11.4 – 127.5 observations

## Requirements
- R (version 4.0 or higher)
- No additional packages required (uses base R only)

## How to run
1. Clone this repository
2. Open R
3. Run the markdown script `Robustified_CUSUM_Code.Rmd’
## Citation
If you use this code, please cite:
[Your paper details once published]

## Contact
Vobo Godlove Watoh
vobo.caleb@yahoo.com
