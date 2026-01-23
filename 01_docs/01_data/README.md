# NYC TLC 2024 Trip Records Analysis - Data Directory

## Overview

This directory contains the datasets used in this project. Because of size limitations, files are not tracked in the Git repository.

*This README serves as a guide to reproduce data*

## Directory Structure

01_data/
├── 01_raw/
├── 02_intermediate/
├── 03_processed/
├── README.md

### 01_raw/

Contains raw records downloaded directly from the official source. Files in this directory should remain unchanged.

### 02_intermediate/

Contains cleaned, filtered, and consolidated datasets produced after initial preprocessing. These datasets are suitable for exploratory data analysis.

### 03_processed/

Contains fully processed, feature engineered datasets used for modeling and final analysis.

## Data Source

**NYC Taxi & Limousine Commission (TLC)**

Source page:
https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

## Data Scope

- **Year:** 2024
- **Vehicle Categories:** All available categories
- **File Format:** Parquet

## Reproducing Data Pipeline

1. Download all 2024 TLC trip records from the official website
2. Place the raw files into 01_data/01_raw
3. Run *02_notebooks/00_data_loading_cleaning.jpynb* to generate datasets in *01_docs/01_data/02_intermediate/*
4. Run *02_notebooks/02_feature_engineering.jpynb* to generate datasets in *01_docs/01_data/03_processed/*
