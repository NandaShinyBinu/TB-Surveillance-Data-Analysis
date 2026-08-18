# U.S. Tuberculosis Surveillance & Data Analysis

## Project Overview

This project analyzes U.S. tuberculosis (TB) surveillance data to identify national and state-level trends, geographic variation, and changes in reported TB incidence over time.

The project combines public health informatics concepts with Python-based data analysis and visualization.

## Research Questions

The analysis investigates:

1. How have reported TB cases changed nationally over time?
2. Which states have the highest TB incidence rates?
3. How have state-level TB incidence rates changed over time?
4. Which states experienced the largest changes in reported TB incidence after 2020?
5. How does state population relate to the number of reported TB cases?
6. Which states have consistently high TB incidence rates?

## Dataset

The analysis uses U.S. tuberculosis surveillance data obtained through CDC WONDER.

The dataset contains state-level information including:

- Year
- State
- State Code
- Reported TB Cases
- Percent of Total Cases
- TB Rate per 100,000 Population
- Population

The analysis covers **1993–2024**.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook / Google Colab
- CDC WONDER
- GitHub

## Data Preparation

The dataset was cleaned and prepared for analysis by:

- Identifying CDC-generated national total and empty rows
- Removing non-state records from the state-level analytical dataset
- Examining missing values
- Converting variables to appropriate numerical data types
- Checking for duplicate observations
- Validating state-level totals against reported national totals

## Analysis

### National TB Trends

The analysis examined changes in reported TB cases over time, with particular attention to the period surrounding 2020.

Reported TB cases increased:

- **9.71% from 2020 to 2021**
- **32.06% from 2021 to 2024**
- **44.88% from 2020 to 2024**

These results indicate a substantial post-2020 rebound in reported TB cases.

### State-Level Analysis

State-level incidence rates were compared using cases per 100,000 population to account for differences in state population size.

Additional analyses examine:

- States with the highest average TB incidence
- Long-term state-level trends
- States with the largest post-2020 changes
- Population versus reported TB cases
- States with consistently high TB incidence

## Public Health Interpretation

The findings describe patterns in reported TB surveillance data and should not be interpreted as direct evidence of changes in underlying TB transmission.

Reported surveillance data may be influenced by factors including healthcare access, testing, diagnosis, healthcare utilization, and reporting practices.

## Future Work

Future stages of the project will incorporate machine learning techniques to explore whether historical surveillance patterns can be used to predict future state-level TB incidence.

Planned methods include:

- Feature engineering using historical TB rates
- Linear Regression
- Random Forest Regression
- Gradient Boosting
- Model evaluation using MAE, RMSE, and R²
- Feature importance analysis
- Anomaly detection

## Author

**Nanda Shiny Binu**

M.S. Data Science — Healthcare Information Technology  
University of Maryland, Baltimore County (UMBC)
