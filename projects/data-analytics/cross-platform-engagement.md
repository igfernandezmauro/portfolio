---
layout: default
title: Content Performance Analysis with Databricks
---

# Content Performance Analysis with Databricks

## Project Overview

This project explores content performance data to understand which measurable factors are associated with higher view counts. The analysis was conducted in Databricks and focuses on exploratory data analysis (EDA) and statistical modeling using multiple linear regression (OLS).

The goal of the project is not prediction at scale, but **interpretation**: identifying relationships between exposure and engagement metrics and understanding their limitations in explaining content performance.

---

## Dataset

The dataset consists of structured content performance metrics, including variables related to impressions, engagement, and views.

**Key characteristics:**
- Structured, tabular data
- Numerical performance and exposure variables
- Single observation per content item
- Target variable: view count

Before analysis, the dataset was reviewed for missing values, distributions, and basic consistency.

---

## Tools & Technologies

- **Databricks**
- **Python**
- **Spark**
- **Pandas**
- **Statsmodels**
- **Matplotlib**

---

## Analytical Approach

### 1. Data Preparation
- Loaded and inspected the dataset in Databricks
- Selected relevant variables for analysis
- Checked for missing values and basic data quality issues
- Prepared the data for exploratory analysis and modeling

---

### 2. Exploratory Data Analysis (EDA)
- Examined distributions of key variables
- Identified skewness and scale differences across metrics
- Explored correlations between views and explanatory variables
- Reviewed pairwise relationships to guide model selection

EDA was used to understand the structure of the data and to inform the regression setup, rather than to draw final conclusions on its own.

---

### 3. Regression Modeling (OLS)

A multiple linear regression model was built using **Ordinary Least Squares (OLS)** to evaluate the relationship between view counts and selected explanatory variables.

Modeling steps included:
- Defining the dependent variable (views)
- Selecting independent variables based on EDA
- Fitting an OLS model using Statsmodels
- Evaluating model fit using R-squared and adjusted R-squared
- Interpreting coefficients, confidence intervals, and p-values

The model was used as an **explanatory tool**, not as a production or predictive system.

---

## Key Findings

- Some exposure-related variables showed statistically significant associations with view counts
- Other engagement metrics had weaker or non-significant relationships
- The model explained a moderate portion of the variance in views, indicating that:
  - observable metrics capture part of performance behavior
  - additional unobserved factors likely influence outcomes

Results were interpreted cautiously, with attention to statistical assumptions and limitations.

---

## Limitations

- Linear regression assumes linear relationships and independence
- The model does not establish causation
- Potential omitted variables may influence results
- Performance metrics alone may not capture qualitative or contextual factors

These limitations were considered when interpreting findings.

---

## Conclusions

This project demonstrates a structured analytical workflow using Databricks:
- Data inspection and preparation
- Exploratory analysis to guide modeling
- Statistical reasoning through regression analysis
- Clear interpretation of results and constraints

The analysis highlights how regression can be used to **understand relationships** in performance data, while also emphasizing the importance of context and limitations.

---

## Project Resources

- Databricks notebook (linked in repository)
- Supporting visualizations and outputs

All analysis steps are reproducible and documented within the notebook.
