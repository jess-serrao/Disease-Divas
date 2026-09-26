# Metastatic Prostate Cancer: Clinical & Genomic Data Analysis

Graduate data-wrangling project analyzing public clinical and genomic data from 150 patients with metastatic castration-resistant prostate cancer (mCRPC).

## Overview

Using R, this project explores relationships among sequencing center, treatment exposure, tumor characteristics, patient age at diagnosis, fraction of genome altered, and mutation count. The analysis emphasizes reproducible data cleaning, exploratory analysis, and clinically relevant feature classification.

## Research Aims

- Aim 1: Volume by center of sequencing
  - 1.1. Analyze aspects of the data against the center of sequencing, search for a possible batch effect, or difference in statistical values based on geographic origin.

- Aim 2: Classify tumor by benign or tumor based on tumor content
  - 2.1. Analyze the tumor content column and possibly come up with a metric based on threshold values to classify a case as malignant or benign based on the data available in the data set.

- Aim 3: Create classification of mutation rate based on mutation count
  - 3.1 Assign classifications of “high”, “medium” or “low” based on the intensity of mutation count.

- Aim 4: Based on mutation count and age of diagnosis come up with prediction of death date
  - 4.1 Perform regression on the available data to possibly predict case outcome and timeline controlling for covariates such as location of exome sequencing and tumor site.

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
