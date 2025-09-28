# House Price Prediction - Advanced Regression Techniques

![Python](https://img.shields.io/badge/Python-3.10-blue)
![ML](https://img.shields.io/badge/Machine-Learning-orange)
![Kaggle](https://img.shields.io/badge/Kaggle-Competition-teal)

A comprehensive machine learning project for predicting house prices using advanced regression techniques and ensemble methods. This project participated in the Kaggle "House Prices: Advanced Regression Techniques" competition.

## 📊 Project Overview

This project tackles the challenge of predicting residential home prices in Ames, Iowa, using 79 explanatory variables describing various aspects of the properties. The solution involves extensive feature engineering, multiple advanced regression models, and ensemble techniques to achieve optimal predictive performance.

## 🏆 Key Features

- **Comprehensive EDA**: Detailed exploratory data analysis with visualizations
- **Advanced Feature Engineering**: Handling of missing values, skewness, and categorical variables
- **Multiple Model Comparison**: XGBoost, LightGBM, CatBoost, Neural Networks, and more
- **Hyperparameter Optimization**: Automated tuning using Optuna
- **Ensemble Methods**: Stacking and blending of best-performing models
- **Kaggle Competition Ready**: Complete pipeline from data cleaning to submission

## 📈 Performance

| Model | Cross-Validation Score (RMSLE) | Public Leaderboard |
|-------|--------------------------------|-------------------|
| XGBoost | 0.1250 | 0.12789 |
| LightGBM | 0.1265 | 0.12845 |
| CatBoost | 0.1278 | 0.12912 |
| Stacked Ensemble | **0.1220** | **0.12567** |

## 🛠️ Installation

### Option 1: Using Conda (Recommended)

```bash
# Create and activate environment
conda env create -f environment.yml
conda activate house-price-prediction

# Launch Jupyter notebook
jupyter notebook
