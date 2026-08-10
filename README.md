# Airbnb Rental Arbitrage

## Identifying High-Value Rental Opportunities in New York City

## Project Overview

This project develops an analytics decision-support tool for evaluating Airbnb rental arbitrage opportunities in New York City.

The goal is to identify apartment characteristics associated with nightly prices above $120 and provide an estimated nightly price before committing to a lease.

The analysis uses a dataset of 4,892 New York City Airbnb listings and applies Multiple Linear Regression to understand the relationship between listing characteristics and nightly price.

## Business Problem

A rental arbitrage investor needs a repeatable way to determine whether a potential apartment may generate enough nightly revenue to support a profitable rental strategy.

The project evaluates factors such as:

- Borough
- Minimum-night requirements
- Number of reviews
- Reviews per month
- Annual availability

## Analytical Method

Multiple Linear Regression was used to estimate nightly rental prices.

The model was evaluated using an 80/20 train-test split.

## Key Findings

- Manhattan had the highest average nightly price.
- Brooklyn and Queens also showed relatively strong pricing.
- Borough was the strongest overall pricing factor.
- Availability had the strongest relationship with price among the continuous variables.
- Review activity had a positive but smaller relationship with price.

## Application Features

The interactive Gradio application includes:

- Market Explorer
- Interactive property filters
- Borough price comparisons
- Listing-level analysis
- Price Simulator
- Model reliability metrics
- Regression coefficient interpretation

## Model Performance

- Test R²: 0.9860
- Test Adjusted R²: 0.9859
- Test MAE: $0.76
- Test RMSE: $5.92

## Tools & Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Gradio
- Matplotlib
- Multiple Linear Regression
- Google Colab

## Business Value

The application provides a practical screening tool for comparing Airbnb rental opportunities. It helps users understand which listing characteristics are associated with higher prices and provides an estimated nightly rate for potential properties.

## Course

MGMT 59000 - AI for Business Analytics  
Purdue University, Daniels School of Business

## Author

Rabia Fatima  
M.S. Business Analytics  
Purdue University
