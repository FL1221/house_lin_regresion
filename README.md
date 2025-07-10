# house_lin_regresion

California Housing Data Analysis
# Overview

This project explores a housing dataset from California, performing preprocessing, visualization, and basic regression modeling to understand factors influencing house prices.


# Dataset Description

The dataset (housing.csv) includes the following features:

longitude / latitude: Geographic coordinates.
housingMedianAge: Median age of buildings in the block.
totalRooms / totalBedrooms: Total rooms and bedrooms per block.
population: Number of residents in the block.
households: Number of households in the block.
medianIncome: Median household income (in tens of thousands USD).
medianHouseValue: Median house value (in USD).
oceanProximity: Categorical variable indicating proximity to the ocean.

# Project Workflow

Data Loading & Exploration:

Read the dataset using pandas.
Display initial rows and check data types.

Preprocessing:

Renamed longitude and latitude for clarity (distance_west, distance_north).
Checked for missing values and handled them.
Basic feature engineering and correlation analysis.

Visualization:

Scatter plots showing geographic distribution of house prices.
Heatmaps and pairplots to understand feature relationships.
Insights revealed that areas near the ocean tend to have higher house values.

Modeling:

Applied a simple Linear Regression model using selected features.
Split data into training and testing sets.
Evaluated model performance using metrics like R² and RMSE.

# Results

- The linear regression model achieved R² = 0.62 on test data.
- Highest house values are located near the coast (e.g. '<1H OCEAN').


# Requirements:

Python 3.x
pandas
numpy
seaborn
matplotlib
scikit-learn
