# Metastatic Prostate Cancer: Clinical & Genomic Data Analysis

Graduate data-wrangling project analyzing public clinical and genomic data from 150 patients with metastatic castration-resistant prostate cancer (mCRPC).

## Overview

Using R, this project explores relationships among sequencing center, treatment exposure, tumor characteristics, patient age at diagnosis, fraction of genome altered, and mutation count. The analysis emphasizes reproducible data cleaning, exploratory analysis, and clinically relevant feature classification.


## Research Aims

- **Aim 1: Assess volume by sequencing center**
  - Analyze data by sequencing center to identify potential batch effects or differences in statistical values by geographic origin.

- **Aim 2: Examine tumor content**
  - Analyze tumor-content values and explore threshold-based classifications using the available data.

- **Aim 3: Classify mutation burden**
  - Assign low-, medium-, and high-mutation-burden categories based on mutation count.

- **Aim 4: Explore associations with clinical outcomes**
  - Assess whether mutation count and age at diagnosis are associated with available outcome measures, controlling for sequencing location and tumor site.

## Data Source

Data were obtained from the public [cBioPortal prostate cancer study](http://www.cbioportal.org/study/clinicalData?id=prad_su2c_2015).

The dataset includes clinical and sequencing-related variables for 150 patients with mCRPC. No patient-identifiable data are included in this repository.

## Methods

- Imported and cleaned clinical data in **R**
- Assessed missingness, variable types, and value distributions
- Created derived categories for mutation burden and tumor-content measures
- Compared measures across sequencing centers and tumor sites
- Produced exploratory visualizations and summary tables

## Tools

- R
- tidyverse
- dplyr
- ggplot2
- R Markdown

## Repository Structure

```text
├── data/             # Data dictionary or instructions for downloading source data
├── notebooks/        # R Markdown analyses
├── scripts/          # Data-cleaning and analysis scripts
├── figures/          # Exported visualizations
├── README.md
└── requirements.R    # R package requirements
