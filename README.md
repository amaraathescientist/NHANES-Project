# NHANES-Project
Investigating Factors Associated With Depressive Symptoms Among U.S. Adults

## Project Overview

This project analyzes depressive symptoms among participants in the [National Health and Nutrition Examination Survey (NHANES)](https://wwwn.cdc.gov/nchs/nhanes/continuousnhanes/default.aspx?Cycle=2021-2023) from the August 2021 to August 2023 cycle using publicly available data from the U.S. Centers for Disease Control and Prevention (CDC).

The project focuses on understanding the distribution of depressive symptoms and examining how they relate to selected demographic, socioeconomic, and health-related factors.

NHANES collects information through interviews, physical examinations, and laboratory testing. The data are released in separate files corresponding to different survey components.

The analysis demonstrates an end-to-end data analytics workflow, including:

* Data acquisition
* Data extraction from SAS transport (.XPT) files
* Data cleaning and preprocessing
* Dataset merging
* Exploratory Data Analysis (EDA)
* Statistical analysis
* Data visualization
* Interpretation of findings
* Documentation of the data-cleaning process

**Note:** NHANES data are distributed across multiple component files, which must be appropriately merged when variables from different components are required for analysis.
## Research Questions

This project investigates the following questions:

1. What is the distribution of depressive symptom scores among NHANES participants?
2. How do depressive symptoms vary across different demographic groups?
3. Is there an association between depressive symptoms and socioeconomic factors?
4. Which factors appear to be associated with higher depressive symptom scores?
5. What patterns can be identified through exploratory and statistical analysis?

**Note:** The analysis is observational and identifies associations rather than establishing causal relationships.

## Data Sources

The project uses publicly available NHANES datasets from the August 2021 to August 2023 cycle, including relevant:

* Demographic data
* Depression screener data
* Body measures data
* Physical activity data
* Sleep disorder data
  
The exact survey cycles and files used in the analysis are documented in the project files.

## Tools & Technologies
### Programming
* Python
* Jupyter Notebook
### Python Libraries
* pandas — data manipulation
* numpy — numerical computing
* matplotlib — data visualization
* seaborn — statistical visualization
* scipy — statistical analysis
* statsmodels — statistical modeling
### Data
* NHANES
* CDC/NCHS

## ⚠️Disclaimer
This project is for educational and analytical purposes. The results should not be interpreted as clinical diagnoses or individual medical advice.
