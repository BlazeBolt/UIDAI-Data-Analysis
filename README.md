Project Overview ---

This repository contains a comprehensive data analysis and visualization project developed on Aadhaar enrolment, demographic updates, and biometric update data published by UIDAI. The project aims to convert large-scale, raw Aadhaar datasets into structured insights that can support policy planning, operational optimization, and risk-aware governance.

The work follows a complete analytics lifecycle, including data ingestion, preprocessing, exploratory data analysis, feature engineering, advanced statistical analysis, and interactive dashboarding using Power BI.

Objectives ---

The primary objectives of this project are:

To analyze Aadhaar enrolment and update patterns across states, districts, and pincodes

To identify operational inefficiencies, service load imbalances, and update backlogs

To detect high-risk and anomalous regions requiring administrative intervention

To visualize inequality in Aadhaar service distribution using advanced analytical techniques

To design decision-ready dashboards suitable for policy review and strategic planning

Repository Structure ---
dataset/

Contains processed and intermediate datasets derived from raw UIDAI data after cleaning, aggregation, and feature engineering. These datasets are structured for analytical modeling and dashboard consumption.

notebooks/

This directory contains all Jupyter notebooks used for data analysis and feature creation.

Key notebooks include:

main.ipynb
Master notebook integrating enrolment, demographic, and biometric analyses.

enrolment.ipynb
Analysis of Aadhaar enrolment distribution, concentration, and inequality.

demographic.ipynb
Analysis of demographic update patterns across age groups and regions.

These notebooks collectively generate the analytical foundation for the Power BI dashboards.

notebooks/outputs/

Contains exported visual outputs generated during exploratory and statistical analysis, including:

Univariate, bivariate, and trivariate plots

Distribution plots and histograms

Boxplots for outlier detection

Correlation heatmaps

Pincode-level and state-level analytical charts

These images are useful for documentation, reports, and presentations.

Raw Data Archives ---

api_data_aadhar_enrolment.zip

api_data_aadhar_demographic.zip

api_data_aadhar_biometric.zip

These compressed files contain the original UIDAI datasets used as input for the analysis. They are preserved for transparency, reproducibility, and auditability.

Analytical Highlights ---

The analysis reveals several critical insights:

Aadhaar enrolment is nearly universal, but operational load is highly uneven across regions

A small fraction of pincodes and states contribute a disproportionately large share of enrolment and updates

Update efficiency varies significantly, indicating capacity and process constraints

Certain regions exhibit persistent child update backlogs, signaling demographic stress

Risk-frontier analysis identifies high-load but underperforming regions requiring targeted intervention

These findings emphasize the need for differentiated, data-driven governance rather than uniform operational policies.
