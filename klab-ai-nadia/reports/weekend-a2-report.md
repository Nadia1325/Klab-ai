# Assignment 2 Report

## Dataset

This analysis used the Car Sales Dataset obtained from Kaggle. The dataset contains approximately 50,000 vehicle records with information about manufacturers, models, engine size, fuel type, year of manufacture, mileage, and price.

## Question Explored

The objective of this analysis was to investigate how vehicle prices vary across manufacturers and how mileage influences vehicle prices. The analysis also aimed to demonstrate data cleaning, feature engineering, and NumPy vectorized computations using a real-world dataset.

## Data Cleaning

The dataset was inspected for missing values, duplicate records, and incorrect data types before analysis. Twelve duplicate rows were identified and removed to avoid repeated observations affecting the results. Data types were validated, and no unnecessary conversions were required.

## Feature Engineering

Several new features were created using Pandas.

A GroupBy operation calculated:

- Average vehicle price by manufacturer
- Average mileage by manufacturer
- Number of vehicles per manufacturer

These statistics were merged back into the original dataset so each record contains both individual vehicle information and manufacturer-level summary information.

A pivot table was also created to compare average prices across manufacturers and fuel types.

## NumPy Computation

The vehicle price column was converted into a NumPy array and standardized using vectorized operations. This produced a new feature called **Standardized_Price**, making prices easier to compare on a common scale.

## Findings

The first visualization showed noticeable differences in average vehicle prices between manufacturers. Premium manufacturers generally had higher average prices than economy manufacturers.

The second visualization indicated that vehicles with higher mileage generally sold for lower prices, although some variation remained across individual vehicles.

## Charts

- Figure 1: Average vehicle prices differ across manufacturers.
- Figure 2: Higher mileage vehicles generally sell for lower prices.

## Limitation

This analysis used only the variables available in the dataset. Other factors that may influence vehicle prices, such as vehicle condition, accident history, optional features, or geographic location, were not available for analysis.