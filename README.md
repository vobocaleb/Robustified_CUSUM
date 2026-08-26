https://doi.org/10.5281/zenodo.22117185

# Robustified CUSUM for Anomaly Detection in Heteroscedastic Streaming Environments

## Overview
This repository contains the code and results for the paper:  
**"Robustified CUSUM for Anomaly Detection in Heteroscedastic Streaming Environments"**  
accepted at ICCIS 2026 (paper PDF will be added after official publication).

## What this project does
- Implements a robustified CUSUM method for anomaly detection
- Uses recursive M-estimators for location and scale
- Adapts to changing variance in real time
- Compares performance with standard CUSUM

## Simulation Scenarios
- **Scenario 1:** No variance change *(not considered — constant variance does not relate to heteroscedasticity)*
- **Scenario 2:** Step variance change + mean shift *(corresponds to Scenario 1 in the paper)*
- **Scenario 3:** Festival spike (UPI-like) *(corresponds to Scenario 2 in the paper)*
- **Scenario 4:** Pure variance change (no mean shift) *(corresponds to Scenario 3 in the paper)*

**Note:** In the R code, scenarios are numbered 2–4. Scenario 1 was omitted because constant variance does not relate to heteroscedasticity.

## Results
- Detection rates: 51.8% – 100%
- Average delays: 11.4 – 127.5 observations

## Requirements
- **R version:** 4.3 or higher
- **RStudio:** Recommended for knitting the .Rmd file

### Required R Packages
```r
install.packages("ggplot2")   # For plotting
```

## How to Run
1. Clone this repository  
2. Open RStudio  
3. Run the markdown script: `Robustified_CUSUM_Code.Rmd`

## License
This project is licensed under the MIT License — see the LICENSE file for details.

## Citation
If you use this code or findings in your own work, please cite:  
> Vobo Godlove W (2026). *Robustified CUSUM for Anomaly Detection in Heteroscedastic Streaming Environments*. Paper presented at ICCIS 2026, BITS Pilani, Goa, India.

## Contact
**Vobo Godlove Watoh**  
Email: vobo.caleb@yahoo.com

