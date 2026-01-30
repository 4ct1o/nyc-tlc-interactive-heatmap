# NYC TLC 2024 Trip Records Analysis

## Problem & Project Objective

Working as a ride-hailing driver involves uncertainty about operating conditions such as time, location, and service selection when attempting to maximize earnings. Demand varies across time, location, and ride-hailing service, which can lead to inefficient driving hours when decisions are made without data-driven insights.

This project aims to analyze New York City TLC High-Volume For-Hire Vehicle trip records from 2024 to identify patterns in earnings-related outcomes across routes, time periods, and ride-hailing platforms.

## Data

**Source:** [NYC TLC trip records](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
High Volume FHV (fhvhv) category for **2024** year
**Size:** 239,470,448 total trips
**Features:** pickup_datetime, dropoff_datetime, request_datetime, trip_miles, trip_time, PULocationID, DOLocationID, base_passenger_fare, tips, tolls, airport_fee, driver_pay, service (selected for analysis)
**Limitations:** Drivers' net earnings are not directly observable in the dataset. There are hidden costs such as fuel and maintenance. Additionally, records do not include driver intent, idle time between trips, or rejected requests, which limits the ability to model full earning efficiency.

## Workflow Overview

(Workflow)

## Analysis Overview 

(Navigate report)

## Project Structure

01_docs/ - Raw and processed datasets, official TLC guides and maps
02_notebooks/ - Jupyter notebooks used for EDA, feature engineering, and analysis
03_src/ - Reusable Python modules for data processing, feature engineering, and modeling
04_reports/ - Final report, figures
05_tests/ - Tests for modules and functions

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

### Captain's temporary log
Jan 24 - duckdb is chosen and learned how to load, combine data - columns will be selected and data will be cleaned