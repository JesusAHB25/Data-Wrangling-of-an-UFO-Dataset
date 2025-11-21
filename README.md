# Data-Wrangling-of-an-UFO-Dataset
Adding a data wrangling section to my portfolio!

## Project Overview

This project provides a comprehensive data quality and cleaning of the historical UFO Sightings dataset from Kaggle. The core goal was to implement robust preprocessing techniques to transform raw, inconsistent data into a high-quality, standardised asset ready for geographic, time-series, and categorical analysis.

## Objective

- **Resolve Datatype Errors:** Format object columns into their correct types, particularly `datetime` for date and time fields and `float` for numeric columns.
- **Implement Text Standardisation:** Apply cleaning rules (`.lower()`, `.strip()`) across all categorical columns (`country`, `UFO_shape`, `city`).
- **Strategically Handle Missing Data:** Determine optimal strategies (imputation vs. deletion) for all null (`NaN`/`NaT`) in the dataset.
- **Validate Geographic Data:** Ensure `latitude` and `longitude` are within valid geographic ranges and free of non-numeric errors.
- **Eliminate Redundancy:** Remove redundant or low-value columns to simplify the final dataset.


## Tools used

- **Python:** Core language for all transformations.
- **Pandas:** Essential for data loading, cleaning, financial transformations, and time series manipulation.
- **NumPy:** Used implicitly by Pandas for high-performance array operations and handling numeric data types.

## Key Results 

- **Global Mapping is Ready:** Coordinate cleaning and strict validation mean we can plot all sightings precisely on a world map with no errors, assuring accurate geographic analysis.
- **The Sighting When and Where is Clean:** By cleaning and converting two date columns, we have a record of when sightings happened and when they were reported.
- **Categories are Unified:** All shapes and locations are standardised, allowing for reliable grouping.
- **The Data is Usable:** The rigorous process guaranteed that the remaining rows are complete and valid, ensuring that the analysis phase will produce trustworthy conclusions.
