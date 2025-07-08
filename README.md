# Predictors of Organ Transplant Outcomes: A Data-Driven Dashboard

##  Project Overview

This project explores the key demographic and clinical predictors of organ transplant outcomes across the United States. We use HRSA (Health Resources & Services Administration) data to visualize post-transplant survival rates, donor types, and disparities in access to care. 

Our analysis and predictive modeling help uncover patterns in 1-year survival and 30-day graft functionality across organ types and transplant centers.

##  Dashboard Preview


The dashboard includes:
- **1-Year Survival by Organ and Donor Type**
- **Age Group and Gender Distribution by Center**
- **Graft vs. Survival Rate Comparison**
- **Transplant Volumes and Insurance Disparities**

##  Research Question

> What are the key demographic or clinical predictors of organ transplant outcomes, and how can these insights be used to improve patient survival rates, graft functionality, and accessibility to transplantation care?

##  Methodology

- Cleaned and merged transplant outcome and demographic data from HRSA
- Removed suppressed and missing values
- Calculated demographic proportions (gender, age)
- Used **Beta Regression** and a **Neural Network (Keras)** to model survival
- Evaluated model performance using **MSE** and **R²**
- Visualized key patterns with Tableau

##  Key Insights

- **Living donor** organs generally lead to higher 1-year survival rates
- **Kidney and liver** transplants showed the most variability across centers
- Survival rates differed across age groups, with older recipients showing slightly lower post-transplant outcomes
- Disparities observed in survival based on insurance type and ethnicity

## Data Source

The data used in this project is publicly available from the U.S. Health Resources & Services Administration (HRSA).

- Data Portal: https://hrsa.gov/
- Source: HRSA Transplant Center Reports and Organ Procurement Organization (OPO) data
- Accessed: March–April 2025

