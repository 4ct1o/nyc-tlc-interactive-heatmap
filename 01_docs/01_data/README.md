# NYC TLC 2024 Trip Records Analysis - Data Directory

## Overview

This directory contains the datasets used in this project. Because of size limitations, files are not tracked in the Git repository.

*This README serves as a guide to reproduce data*

## Directory Structure

01_data/
├── 01_raw/
├── 02_processed/
├── README.md

### 01_raw/

Contains raw records downloaded directly from the official source. Files in this directory should remain unchanged.

### 03_processed/

Contains fully processed, feature engineered datasets used for visualizing.

## Data Source

**NYC Taxi & Limousine Commission (TLC)**

Source page:
https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

## Data Scope

- **Year:** 2024
- **Vehicle Categories:** FHV, FHVHV, Green, Yellow
- **File Format:** Parquet

## Reproducing Data Pipeline 

1. Download all 2024 TLC trip records from the official website
2. Place the raw files into 01_data/01_raw
3. Run *02_notebooks/01_data_preparation.jpynb* to generate dataset in *01_docs/01_data/02_processed/*
