# US_House_price_prediction_using_key_Indicators
Certainly! Here's a sample README file for the provided analysis:

---

# US Housing Market Analysis

## Overview

This repository contains a Jupyter Notebook (`us_housing.ipynb`) that analyzes key factors influencing the US housing market. The analysis utilizes data collected from the Federal Reserve Economic Data (FRED) website, spanning the past 20 years.

## Key Indicators Explored

The analysis focuses on several key indicators known to influence US house prices, including:

- GDP (Gross Domestic Product)
- Employment statistics
- Labor force participation rate
- Computer and software sales
- Case-Shiller U.S. National Home Price Index
- Employment-to-population ratio
- Housing starts
- 30-Year Fixed Rate Mortgage Average
- Manufacturers' shipments, inventories, and orders
- Median sales price of houses sold
- Industrial production of durable and non-durable goods
- Building permits
- Personal income
- Population
- Personal saving rate
- Real sales for retail and food services
- University of Michigan Consumer Sentiment Index
- Total unemployed, plus discouraged workers
- Unemployment rate

These indicators offer insights into economic performance, employment, housing market trends, consumer sentiment, and overall economic activity.

## Data Cleaning and Merging

The data from various sources are cleaned, resampled, and merged into a single dataset. The cleaning process involves handling missing values, date formatting, and saving cleaned data files for each indicator.

## Data Exploration

Exploratory Data Analysis (EDA) is performed, including distribution plots and box plots for each key indicator. Outliers are identified and removed using Interquartile Range (IQR) method, and the data is checked for normality using the Shapiro-Wilk test.

## Correlation Analysis

The correlation between house prices and other variables is explored using a heatmap. The analysis identifies factors positively and negatively correlated with house prices.

## Feature Selection

Lasso Cross Validation is applied to select the most relevant features for predicting house prices. The selected features are used to create a subset of independent variables.

## Model Building and Evaluation

Linear Regression models are built using all independent variables and the selected subset. The models are evaluated on both training and test datasets, and R-squared values are used to assess model accuracy.

## Key Insights

The analysis provides key insights into the factors influencing US house prices, including supply and demand dynamics, economic indicators, and market sentiment.

## Conclusion

Understanding these factors is valuable for stakeholders in the real estate market, informing decisions related to investments, financing, and economic policies.

---

Feel free to customize and expand this README to better suit your specific project details and context.
