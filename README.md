
# Retail Store Location Optimization

This project focuses on optimizing retail store locations in New York City through a data-driven approach. By analyzing pedestrian traffic, competition, and vacant storefront availability, businesses can strategically expand, minimize operational costs, gain a competitive edge, and reduce the risk of underperformance.



## Key Features

**Data Normalization and Weight Assignment:**
We normalized data and assigned weights (Pedcounts: 0.4, Retail Stores: 0.4, Vacant Storefronts: 0.2) using min-max scaling.

__Suitability Score Calculation:__
The combined suitability score reflects weighted features, ranking locations based on preferences.

__Regression Models:__
Utilizing various regression models (Random Forest, Linear Regression, Gradient Boosting, XGBoost, SVR, Ridge Regression) for predicting continuous location suitability scores.

__Model Selection Rationale:__
Each regression model contributes unique strengths: Random Forest captures complex relationships, Linear Regression serves as a baseline, Gradient Boosting corrects errors iteratively, XGBoost ensures speed and efficiency, SVR excels in high-dimensional spaces, and Ridge Regression prevents overfitting.


## Appendix

Project for CS-GY 6053 Foundation of Data Science at NYU Tandon.

