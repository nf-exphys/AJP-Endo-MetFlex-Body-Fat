# AJP-Endo-MetFlex-Body-Fat
This repository contains analysis datafiles and a Colab notebook for our short report in AJP-Endo on body fat percentage and metabolic flexibility.

Follow the steps below to reproduce our main and supplemental results:

1) Download analysis.zip.
2) Click AJP_Endo_MetFlex_Body_Fat_Analysis.ipynb and click "Open in Colab".
3) Follow the instructions in the Colab notebook to upload the analysis.zip file. This will require a Google account.
4) Run all cells in the notebook.

The analysis.zip file contains three files:
1) _analytic_sample_mean_sd.csv_ has the means and standard deviations for variables in the main analyses. These are used within the notebook to back-transform data from their centered and scaled values to typical values.
2) _postprandial_analysis.csv_ has covariates and outcome variables for the mixed effects model analyses. All data in this file is centered to mean 0 with a SD of 1.0. Note this data is in long format, so any constant covariates (i.e., sex, body fat, etc.) appear four times per participant, one for each postprandial timepoint.  
3) _other_data.csv_ has the raw data for Table 1 not otherwise included in other files. All data in this file is in its typical units (i.e., not centered and scaled).
