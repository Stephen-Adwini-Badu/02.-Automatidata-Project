# Automatidata Project

## Overview
This project is part of the Google Advanced Data Analytics curriculum and focuses on analyzing taxi fare data to derive actionable insights. The project consists of two primary objectives:

1. **Two-Sample T-Test Analysis**: Investigate the relationship between the total fare amounts of credit card payment users and cash payment users.
2. **Regression Model Development**: Build a predictive model to estimate taxi fares based on available data.

## Objectives
### Objective 1: Two-Sample T-Test
- **Hypotheses**:
  - **Null Hypothesis (H₀):** There is no significant difference in the average fare amounts between credit card and cash payment users.
  - **Alternative Hypothesis (H₁):** There is a significant difference in the average fare amounts between credit card and cash payment users.
- **Insight Goal**: Determine whether promoting credit card payments could potentially generate more revenue for taxi drivers.

### Objective 2: Regression Model
- **Goal**: Construct a regression model to predict taxi fares using the provided dataset.
- **Use Case**: Enhance pricing strategies and fare estimation systems for taxi services.

## Methodology
### Data Preparation
- Importing necessary packages for statistical and machine learning analysis.
- Cleaning and preprocessing the data to ensure accuracy and consistency for analysis.

### Analysis and Testing
1. **Two-Sample T-Test**:
   - Compare the means of fare amounts between two groups: credit card and cash users.
   - Assess the p-value to determine statistical significance.

2. **Regression Modeling**:
   - Feature engineering to identify relevant predictors for fare estimation.
   - Split the data into training and testing subsets.
   - Train and evaluate the model using metrics such as R-squared and mean squared error.

### Insights
- Analyze the results of the t-test to guide payment method recommendations.
- Evaluate the performance of the regression model to ensure it provides accurate predictions.

## Requirements
The project uses the following Python packages:
- **pandas**: For data manipulation.
- **numpy**: For numerical computations.
- **scipy**: For statistical testing.
- **scikit-learn**: For regression modeling and evaluation.
- **matplotlib/seaborn**: For data visualization.

## Results
- Key findings from the statistical test and regression analysis will guide data-driven decisions for improving taxi service operations.
