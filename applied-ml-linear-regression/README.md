# Lab 3: Linear Regression with Scikit-Learn

## Lab Title
**"Linear Regression: Simple and Multiple Regression"**

## Overview
This lab explores linear regression techniques using the scikit-learn library and the California Housing dataset. The lab demonstrates:

- Loading and exploring the California Housing dataset
- Understanding data preprocessing and missing value checking
- Implementing Simple Linear Regression with single features
- Building Multiple Regression models with multiple features
- Comparing model performance using evaluation metrics (MSE, MAE, RMSE)
- Visualizing actual vs predicted values

## Dataset
- **Source**: sklearn.datasets.fetch_california_housing
- **Features**: MedInc, HouseAge, AveRooms, AveBedrms, Population, AveOccup, Latitude, Longitude
- **Target**: House value (in $100,000s)

## Experiments Performed
1. **Simple Linear Regression** - Using AveBedrms feature
2. **Simple Linear Regression** - Using AveRooms feature
3. **Multiple Regression (2 features)** - Using AveBedrms and AveRooms
4. **Multiple Regression (4 features)** - Using AveBedrms, AveRooms, MedInc, HouseAge

## Evaluation Metrics
- **MSE** (Mean Squared Error)
- **MAE** (Mean Absolute Error)
- **RMSE** (Root Mean Squared Error)

## Directory Structure
```
applied-ml-linear-regression/
├── linear_regression.ipynb    # Main Jupyter notebook with all experiments
└── README.md                 # This file
```

## Getting Started
1. Clone the repository.
2. Install required packages:
   ```bash
   pip install scikit-learn pandas numpy matplotlib seaborn
   ```
3. Open `linear_regression.ipynb` in Jupyter Notebook or JupyterLab.
4. Run the cells sequentially to see the regression experiments.

## Libraries Used
- pandas - Data manipulation
- numpy - Numerical operations
- matplotlib & seaborn - Visualization
- scikit-learn - Machine learning algorithms and metrics

## License

This project is for educational purposes.
