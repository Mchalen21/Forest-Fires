# Forest-Fires
# Forest Fire Prediction

## Project Overview
This project analyzes the Forest Fires dataset to predict burned forest area using meteorological data.

## Project Structure

data/
notebooks/
explore.ipynb
clean.ipynb
model.ipynb

## Step 1: Data Exploration
Initial exploration was performed to understand dataset structure, detect missing values, and visualize variable distributions.

## Step 2: Data Cleaning
Duplicate records were removed and categorical variables were encoded.

## Step 3: Feature Engineering
A log transformation was applied to the target variable due to skewness.

## Step 4: Model Building
Baseline regression models were trained including Linear Regression and Random Forest.

## Results
Random Forest produced better performance than Linear Regression, indicating nonlinear relationships between meteorological variables and fire size.