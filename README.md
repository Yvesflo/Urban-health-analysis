# Urban-health-analysis
This repository is to store and share the analysis scripts of various analysis I done for my training or ongoing works. the dataset are not shared but feel free to use them to adapt for your analytics, drop me a message for anything I could help
# R Scripts for Climate and Health Analysis

A collection of clean R scripts for analyzing climate patterns and health data. These scripts are designed to be easily copied and adapted for your own datasets.

## Scripts Overview

| Script | Purpose |
|--------|---------|
| `extreme_rainfall_analysis.R` | Analyze extreme rainfall patterns and trends |
| `cardiovascular_risk_analysis.R` | Cardiovascular risk modeling with ordinal regression |
| `air_pollution_interpolation.R` | Spatial interpolation of air pollution data |
| `uhi_rainfall_analysis.R` | Urban heat island and rainfall correlation analysis |
| `spatial_health_analysis.R` | Spatial analysis of health behaviors |
| `mca_analysis.R` | Multiple correspondence analysis of health behaviors |
| `time_series_analysis.R` | Time series forecasting of climate data |

## Usage

1. Copy the script you need
2. Adapt the data loading section for your files
3. Modify variable names to match your data
4. Run the analysis

## Required R Packages

```r
install.packages(c("readxl", "dplyr", "ggplot2", "sf", "mgcv", "nnet", 
                   "tsibble", "fable", "corrplot", "FactoMineR"))
