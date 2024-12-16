# Choline MRS Meta-Analysis in Psychosis Spectrum Disorders

This repository contains the code and analysis scripts for a series of meta-analyses and meta-regressions exploring choline levels in psychosis spectrum disorders using magnetic resonance spectroscopy (MRS). The analyses are designed to investigate differences the in magnitude and variability of choline metabolites across different diagnostic groups and brain regions.

## Repository Structure

- **`choline_MA_casecont.Rmd`**: Meta-analysis of all psychosis cases vs controls, integrating data cleaning and forest plot generation.  
- **`choline_MA_established_psychosis.Rmd`**: Meta-analysis focused on choline levels in individuals with established psychosis group vs controls.  
- **`choline_MA_all_diagnoses.Rmd`**: Meta-analysis comparing choline levels in all specific psychosis spectrum diagnoses versus healthy controls.  
- **`Choline_MRS_Metaregressions.Rmd`**: Conducts meta-regressions to examine factors influencing choline levels across studies.  

## Requirements

The analysis scripts require the following R packages:

- `tidyverse`  
- `metafor`  
- `readxl`  
- `RColorBrewer`  
- `writexl`  
- `ggplot2`  
- `grid`  

Install these packages with:
```R
install.packages(c("tidyverse", "metafor", "readxl", "RColorBrewer", "writexl", "ggplot2", "grid"))
```
## Data Preparation
Modify the file paths in each script's setwd() function to match your data directory.

## Outputs
Each script generates:
1. Forest Plots: Visual comparisons of choline levels across brain regions.
2. Summary Tables: Results for SMD, CVR, and VR analyses saved as Excel files.
3. Funnel Plots: Visualizations for publication bias assessments.

## Author
Dr Cameron Watson
[Email Me](mailto:cameron.watson@kcl.ac.uk)

