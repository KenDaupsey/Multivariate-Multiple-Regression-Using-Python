# Multivariate-Multiple-Regression-Using-Python

## Introduction
This repository demonstrates the application of multivariate multiple regression analysis, a statistical technique used to examine relationships between multiple independent variables and two or more dependent variables simultaneously.

## Overview
The code provided implements multivariate multiple regression analysis using Python libraries such as pandas and statsmodels. The analysis is performed on a dataset containing variables such as 'male,' 'female,' 'math,' 'science,' 'socst,' 'write,' and 'read.'

## Procedure
1. **Data Preparation**: The dataset, assumed to be loaded into a pandas DataFrame named 'df,' is preprocessed to handle categorical variables using one-hot encoding.
2. **Modeling**: Two separate linear regression models are fitted for the dependent variables 'write' and 'read' using the predictors defined from the dataset.
3. **Analysis**: The resulting coefficients, R-squared values, and p-values are examined to understand the relationships between predictor variables and the respective outcomes.

## Key Features
- **Multivariate Analysis**: Understand how various predictors collectively influence multiple outcomes.
- **Interpretation**: Gain insights into the impact of predictor variables on 'write' and 'read' scores.
- **Policy Implications**: Inform decision-making based on statistical analysis results.

## Usage
1. Ensure Python and required libraries are installed.
2. Clone the repository and navigate to the directory.
3. Run the provided Python script to perform multivariate multiple regression analysis on your dataset.

## Conclusion
This repository serves as a valuable resource for researchers, analysts, and decision-makers seeking to explore complex relationships within multivariate datasets and make data-driven decisions based on regression analysis results. Explore the code and adapt it to your specific analysis needs.
