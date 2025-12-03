# STOR-664-Pokemon-Analysis

## Team Members

-   Kareena Legare (@kareenalegare)

-   Sam Moore (@sammoore64)

-   Yin Yu Yao (@YinYuYYY)

-   Irene Zhang (@yilu0601)

## Overview

This repository contains the final group project for STOR 664, Fall 2025. Our goal is to analyze which characteristics of Pokemon best predict their HP stat with data containing Pokemon information such as stats using t-tests and F-tests to test our hypotheses.

## Repository Structure

| Folder | Purpose | Key Files |
|----|----|----|
| /data/processed | Cleaned datasets ready for analysic | `pokemon_processed.csv` |
| /data/raw | Original unmodified datasets | `pokemon_raw.csv` |
| /reports | All written deliverables | `01_load_data-EDA.pdf` |
| /results/figures | Visual outputs | `k_hypothesis_triptych.png` |
| /results/tables | Numeric summaries | `count_by_type1.csv` |
| /src | Analysis and visualization code | `01_load_data&EDA.Rmd` |

## Getting Started

### 1. Clone the repository

`git clone https://github.com/kareenalegare/STOR-664-Final-Project.git`

### 2. Running Analysis Scripts

`Rscript src/01_load_data&EDA.Rmd`
`Rscript src/02_data_analysis.Rmd`

## Acknowledgements

ChatGPT was used to assist with code implementation and editing. Yin and Kareena performed the exploratory data analysis and created the figures in Part 1. Kareena implemented the hypothesis test code in Part 2. Yin implemented the diagnostic plots in Part 2. Irene wrote the narrative portions of the reports. Sam prepared the presentation.
