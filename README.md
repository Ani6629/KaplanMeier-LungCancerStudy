# KaplanMeier-LungCancerStudy

![Survival Analysis]([link-to-image-if-any](https://drive.google.com/file/d/1ZYoIcLSzRbaQ6Fzj0h3igKTJwwBfV-je/view?usp=sharing))

## Project Overview

This project explores survival analysis in patients with advanced lung cancer, investigating the role of gender in survival outcomes. It uses the Kaplan-Meier estimator for survival analysis and the Log Rank Test to compare survival distributions between male and female patients.

## Dataset Description

The dataset is the NCCTG Lung Cancer Data from the North Central Cancer Treatment Group, encompassing survival time, age, gender, performance scores, meal calories, and weight loss data.

## Dependencies

The Python packages required to run the code are:

- pandas
- lifelines
- matplotlib

You can install these packages using pip:
!pip install lifelines
!pip install pandas
!pip install matplotlib

# Code Description

The code includes several stages:

# Data Transformation: 

- Recoding 'status' from 1/2 to 0/1.
- Kaplan-Meier Estimation: Calculation of survival probabilities over time.
- Plotting Survival Curves: Visual representation of the survival probabilities.
- Log Rank Test: Testing for differences in survival distributions between male and female patients.
- Results
The analysis reveals a significant difference in survival rates between male and female patients. This finding emphasizes the need for gender-specific treatment strategies in advanced lung cancer management.

# References

Loprinzi CL. et al. Prospective evaluation of prognostic variables from patient-completed questionnaires. North Central Cancer Treatment Group. Journal of Clinical Oncology. 12(3):601-7, 1994.
