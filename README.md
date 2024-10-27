# Cold Tolerance Analysis of *A. valentianus*

This repository contains the code and data for analyzing the cold tolerance of *A. valentianus*.
The analysis explores different physiological and survival aspects of the species when exposed to cold temperatures, providing insights into potential strategies used to cope with freezing conditions.

## Directory Structure:

### Data Directory:

The data/ folder contains the datasets used for the analysis, which are listed below:

-   data/coldvsfreeze.csv: Data for the cold vs freezing experiment.

-   data/concentrations_names.csv: Names and descriptions of metabolites found in analysis (output from Bayesil).

-   data/metabolite_groups.csv: Groupings of metabolites for the analysis, used to make table in the results.

-   data/new_wet_conc_moles.csv: Metabolite concentrations in molar units, adjusted for wet weight.

-   data/slug_weights.csv: Recorded weights of individual slugs used in the experiments (both dry and wet weight).

-   data/survival_original.csv: Original survival data under various acclimation conditions.

### Scripts Directory:

The scripts/ folder contains R Markdown files and their corresponding outputs used in the analysis:

-   scripts/freeze_vs_cold.Rmd and scripts/freeze_vs_cold.pdf: Analysis for the cold vs freezing experiment.

-   scripts/NMR_analysis.Rmd and scripts/NMR_analysis.pdf: H Nuclear Magnetic Resonance (H NMR) data analysis for metabolite profiling.

-   scripts/survival_by_bodyweight.Rmd and scripts/survival_by_bodyweight.html: Analysis of survival, SCP, body weight, and body water content in response to acclimation conditions

### Usage 

To replicate the analysis, ensure you have the required R packages installed.
The R Markdown (.Rmd) files can be rendered to generate the analysis reports, while the data files provide the necessary datasets for each script.

