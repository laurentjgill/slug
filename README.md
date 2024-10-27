# Cold Tolerance Analysis of *A. valentianus*

This repository contains the code and data for analyzing the cold tolerance of *A. valentianus*. The analysis explores different physiological and survival aspects of the species when exposed to cold temperatures, providing insights into potential strategies used to cope with freezing conditions.

## Directory Structure:

### Data Directory:

The data/ folder contains the datasets used for the analysis, which are listed below:

-   data/coldvsfreeze.csv: Data for the cold vs freezing experiment, columns listed below.

    -   acclimation_day_length: Length of day during the acclimation period (Long day LD for all).

    -   acclimation_length_days: Duration of acclimation (in days).

    -   acclimation_temp: Temperature during the acclimation period (all 15 degrees Celsius).

    -   bath_temp_at_scp: Temperature of the bath when the supercooling point (SCP) was reached.

    -   cold_exposure_begin: Start time of the cold exposure.

    -   cold_exposure_length: Duration of the cold exposure (in minutes).

    -   date_frozen: Date when the slug was frozen.

    -   exposure_temp: Temperature during exposure (in degrees Celsius).

    -   frozen: Whether the slug was frozen (0/1).

    -   minutes_cold: Total time spent in cold conditions (in minutes).

    -   scp: Supercooling point temperature (in degrees Celsius).

    -   slug_number: Identifier for each individual slug.

    -   survival: Whether the slug survived (0/1).

    -   time_spent_frozen: Duration for which the slug remained frozen (in minutes).

    -   time_stamp_end: End time of the cold exposure.

    -   time_stamp_freeze: Time when the slug began to freeze.

    -   treatment: Type of experimental treatment applied (photoperiod + temp).

    -   weight: Weight of the slug (in grams).

-   data/concentrations_names.csv: Names and descriptions of metabolites found in analysis (output from Bayesil).

-   data/metabolite_groups.csv: Groupings of metabolites for the analysis, used to make table in the results.

-   data/new_wet_conc_moles.csv: Metabolite concentrations in molar units, adjusted for wet weight.

-   data/slug_weights.csv: Recorded weights of individual slugs used in the experiments (both dry and wet weight).

    -   dry_weight_g: Dry weight of the slug (in grams).

    -   slug_number: Identifier for each individual slug.

    -   wet_weight_g: Wet weight of the slug (in grams).

-   data/survival_original.csv: Original survival data under various acclimation conditions.

    -   acclimation_day_length: Length of day during the acclimation period (SD or LD).

    -   acclimation_length_days: Duration of acclimation (in days).

    -   acclimation_temp: Temperature during the acclimation period (in degrees Celsius).

    -   averageSCP: Average supercooling point temperature for the slug (in degrees Celsius).

    -   bathtemp_at_SCP: Temperature of the bath when the SCP was reached.

    -   channel1SCP: SCP recorded from channel 1.

    -   channel2SCP: SCP recorded from channel 2.

    -   minutes_frozen: Duration for which the slug remained frozen (in minutes).

    -   slug_number: Identifier for each individual slug.

    -   survival: Whether the slug survived (0/1), assessed after 24 hours (refer to methods).

    -   time_stamp_begin: Start time of the freezing experiment.

    -   time_stamp_freeze: Time when the slug began to freeze.

    -   time_until_freezing: Time taken for the slug to freeze (in minutes).

    -   treatment: photoperiod+temp.

    -   weight: Weight of the slug (in grams).

### Scripts Directory:

The scripts/ folder contains R Markdown files and their corresponding outputs used in the analysis:

-   scripts/freeze_vs_cold.Rmd and scripts/freeze_vs_cold.pdf: Analysis for the cold vs freezing experiment.

-   scripts/NMR_analysis.Rmd and scripts/NMR_analysis.pdf: H Nuclear Magnetic Resonance (H NMR) data analysis for metabolite profiling.

-   scripts/survival_by_bodyweight.Rmd and scripts/survival_by_bodyweight.html: Analysis of survival, SCP, body weight, and body water content in response to acclimation conditions

### Usage

To replicate the analysis, ensure you have the required R packages installed. The R Markdown (.Rmd) files can be rendered to generate the analysis reports, while the data files provide the necessary datasets for each script.
