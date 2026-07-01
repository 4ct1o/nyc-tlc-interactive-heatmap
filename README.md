# NYC TLC Heatmap

## Problem & Project Objective

Ride-hailing demand varies throughout the day across different areas of New York City.

This project aims to help track ride demand across New York City by location and time of day using an interactive heatmap.

## Showcase
![Video](03_outputs/nyc_number_of_pickups.mp4)
## Data

**Source:** [NYC TLC trip records](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
High Volume FHV (fhvhv) category for **2024** year
**Size:** 298,930,712 total trips
**Features:** pickup_datetime, request_datetime, PULocationID
**Limitations:** Zones provide aggregated geographic regions rather than exact GPS coordinates limiting the resolution. Dataset records completed trips and does not include unmet demand, rejected requests. External factors which may influence demand such as weather, traffic conditions, and public events are not incorporated into the analysis.

## Workflow Overview

(Workflow)

## Analysis Overview 

(Navigate report)

## Project Structure

**01_docs/** - Raw and processed datasets, official TLC guides and maps
**02_notebooks/** - Jupyter notebooks used for EDA, feature engineering, and analysis
**03_src/** - Reusable Python modules for data processing, feature engineering, and modeling
**04_reports/** - Final report, figures
**05_tests/** - Tests for modules and functions

## Tools & Technology

Programming language: **Python**
Core libraries: **pandas, matplotlib, seaborn, scikit-learn, duckdb, pyarrow**
*Versions are included in* **requirements.txt**


## Reproducibility & Setup

(Instructions for reproducibility)


## Limitations & Future Work

(Data limitations, possible improvements)

## References

## License