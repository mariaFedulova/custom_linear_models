# Property Price Prediction: Regression Models

Implementation and comparison of linear regression models with regularization for real estate price prediction.

## Overview

This project explores regression techniques for predicting apartment prices based on numerical features (bathrooms, bedrooms) and categorical amenities extracted from property descriptions.

- Manual implementation of Linear Regression, Ridge, Lasso, and ElasticNet
- Feature engineering from unstructured text data
- Polynomial feature expansion for non-linear relationships
- Regularization techniques to prevent overfitting
- Feature normalization (MinMax, Standard scaling)
- Comparison with scikit-learn implementations

## Data

Apartment listings with:
- Numerical: `bathrooms`, `bedrooms`
- Text: `Features` (amenities list)
- Target: rental price

Preprocessing:
- Extracted 20 most frequent amenities from text descriptions
- Created binary indicators for each
- Combined with numerical features (22 total)

## Results

Performance metrics (MAE, RMSE, R²) tracked across all models, with comparisons between custom implementations and scikit-learn to validate correctness.

## Contents
- `supervised_learning.ipynb` – main implementation
- `data/` – folder containing the dataset (not included in repo)
- `README.md` – project description
