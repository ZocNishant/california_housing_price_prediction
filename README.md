# California Housing Price Prediction

## Problem

Predict median house prices in California based on location and demographics.

## Dataset

- 20,640 houses in California
- 8 features: Income, Age, Rooms, Location, etc.
- Target: Median house value

## What I Did

1. Explored data (no missing values, clean dataset)
2. Trained 3 regression models
3. Compared performance using MAE, RMSE, R²
4. Analyzed feature importance

## Results

- **Random Forest: R² = 0.804** (Winner!)
- Linear Regression: R² = 0.576
- Decision Tree: R² = 0.626

## Key Insight

MedInc (Median Income) is the most important feature - explains 52.6% of prediction power.

## Technologies Used

Python, Pandas, Scikit-learn, Random Forest Regressor
