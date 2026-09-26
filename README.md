# Metastatic Prostate Cancer: Clinical & Genomic Data Analysis

Graduate data-wrangling project analyzing public clinical and genomic data from 150 patients with metastatic castration-resistant prostate cancer (mCRPC).

## Overview

Using R, this project explores relationships among sequencing center, treatment exposure, tumor characteristics, patient age at diagnosis, fraction of genome altered, and mutation count. The analysis emphasizes reproducible data cleaning, exploratory analysis, and clinically relevant feature classification.

## Research Questions

- Is there evidence of variation in clinical or genomic measures by sequencing center?
- How do tumor content, treatment exposure, tumor site, and mutation burden vary across patients?
- Can mutation count be categorized into low-, medium-, and high-burden groups?
- What relationships are present between age at diagnosis, tumor characteristics, and genomic alteration?

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
