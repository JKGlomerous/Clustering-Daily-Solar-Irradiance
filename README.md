# Clustering Daily Solar Irradiance Patterns

## Project Overview

This repository contains the R code developed for a BSc Honours research project in Mathematical Statistics at Nelson Mandela University (2026).

The project investigates daily solar irradiance patterns at five South African locations using hourly data obtained from the Copernicus Atmosphere Monitoring Service (CAMS). An adapted two-level clustering framework is applied to identify seasonal groups and classify daily irradiance patterns.

## Methodology

The analysis consists of the following procedures:

1. **Data preprocessing:** Preparation of hourly CAMS irradiance observations into complete daily profiles.
2. **Seasonal clustering:** Application of k-means clustering to standardised clear-sky features to identify Summer, Winter and Transition groups.
3. **Daily irradiance classification:** Application of k-means clustering to the Daily Irradiance Index (β) to classify days into High, Medium and Low irradiance categories within each season.
4. **Clustering comparison:** Comparison with Partitioning Around Medoids (PAM) using Euclidean Distance (ED) and Dynamic Time Warping (DTW) on hourly irradiance profiles.
5. **Cluster evaluation:** Assessment using internal validation indices and the Adjusted Rand Index (ARI).
6. **Bootstrap stability assessment:** Evaluation of clustering stability through 1,000 bootstrap replications.

## Repository Contents

**DataAnalysisL1.Rmd** — R Markdown file containing the complete data preprocessing, clustering, evaluation and bootstrap analysis for Location L1 (Kalkbult Solar Park).

The same analytical procedures were applied to the remaining four locations (L2–L5), with the input datasets and location-specific parameters adjusted accordingly. Therefore, the L1 code is provided as the representative implementation of the methodology used throughout the study.

## Data Availability

The solar irradiance data used in this study were obtained from CAMS. The original datasets are not included in this repository and must be obtained separately to reproduce the analysis.

## Author

Wehan Smith

BSc Honours in Mathematical Statistics

Nelson Mandela University, South Africa

2026
