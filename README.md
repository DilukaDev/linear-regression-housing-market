# Linear Regression Housing Market

A machine learning project that predicts California housing prices using linear regression on the California housing dataset.

## Overview

This project demonstrates a complete machine learning workflow:

- Loading and exploring the California housing dataset
- Building and training a linear regression model
- Evaluating model performance
- Visualizing predictions
- Making price predictions for new data

## Dataset

Uses the **California Housing Dataset** from scikit-learn, which contains housing prices and features for California census block groups from 1990.

### Features

- **MedInc**: Median income in the block group
- **HouseAge**: Median house age in the block group
- **AveRooms**: Average number of rooms per household
- **AveBedrms**: Average number of bedrooms per household
- **Population**: Block group population
- **AveOccup**: Average household occupancy
- **Latitude**: Block group latitude
- **Longitude**: Block group longitude

### Target

- **median_house_value**: Median house value (in $100,000s)

## Model Performance

- **Mean Squared Error (MSE)**: 0.56
- **R² Score**: 0.58
