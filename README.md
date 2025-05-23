# Analysis of Suicide Rates in the USA by Gender, Race, and Age Groups (1950-2018)

## Overview
This project analyzes long-term trends in suicide rates in the United States, focusing on different age groups, gender, and race. The analysis aims to better understand factors influencing suicide risk and identify high-risk groups to support more effective preventive policies.

## Project Goals
- Examine long-term trends in suicide rates from 1950 to 2018
- Analyze differences in suicide rates based on gender, race, and age groups
- Identify patterns and risk factors across different demographic groups

## Data Source
The data used in this analysis comes from:
- National Vital Statistics System (NVSS)
- U.S. Census Bureau
- Specific sources:
  - Grove RD, Hetzel AM. "Vital statistics rates in the United States, 1940-1960"
  - NVSS annual public-use Mortality Files
  - Murphy SL, Xu JQ, Kochanek KD, Arias E, Tejada-Vera B. "Deaths: Final data for 2018"
  - Dataset available on Kaggle: [Death Rates United States](https://www.kaggle.com/datasets/melissamonfared/death-rates-united-states)

## Dataset Structure
The dataset includes the following key columns:
- `INDICATOR`: Death rates for suicide
- `UNIT`: Measurement units (Deaths per 100,000 resident population)
- `STUB_NAME`: Categories including sex, age, race, and Hispanic origin
- `YEAR`: Data from 1950-2018
- `AGE`: Various age groups from "All ages" to specific ranges
- `ESTIMATE`: Death rate value

## Requirements
- Python 3.x
- Required libraries:
  - pandas
  - kagglehub
  - shutil

## Analysis Components
The analysis includes:
- Data loading and initial exploration
- Basic statistical analysis
- Demographic breakdowns
- Time series analysis of trends
- Detailed examination of specific demographic groups

