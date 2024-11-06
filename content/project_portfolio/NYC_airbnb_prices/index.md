---
title: 'NYC Airbnb Price Prediction'
date: 2023-04-10
tags: [
    "Machine Learning",
    "Data Analysis",
    "Ensemble Learning",
    "Statistical Analysis",
    "Regression Analysis"
]
image: 'cover.jpg'
github: 'https://github.com/dasjyotishka/Predicting-Airbnb-Prices-in-New-York-City'
draft: false
---

Developed a comprehensive machine learning system for predicting Airbnb prices in New York City, achieving 62.87% accuracy on test data using XGBoost. The project incorporated extensive exploratory data analysis, feature engineering, and model optimization, comparing various regression algorithms including classical ML models and ensemble methods.

<!--more-->

## Overview
The project addresses the challenge of accurately predicting Airbnb listing prices in New York City using a dataset of over 48,000 listings. Through systematic implementation of data preprocessing, exploratory analysis, and advanced modeling techniques, the study demonstrates the superiority of ensemble methods in price prediction. The research particularly focused on feature engineering and hyperparameter optimization, resulting in robust predictive performance across different evaluation metrics.

## Technologies
- **Programming**: Python, Jupyter Notebooks
- **Data Processing**: Pandas, NumPy
- **Machine Learning**: Scikit-learn, XGBoost, CATBoost
- **Data Visualization**: Matplotlib, Seaborn, Yellowbrick
- **Feature Engineering**: One-hot Encoding, Standard Scaling
- **Statistical Analysis**: SciPy, StatsModels
- **Model Evaluation**: Cross-validation, Various Metrics
- **Hyperparameter Optimization**: RandomizedSearchCV

## Implementation Details

### 1. Data Preprocessing and EDA
- Analyzed 48,000+ NYC Airbnb listings
- Implemented comprehensive outlier detection and removal
- Developed visualization pipeline for feature relationships
- Created correlation analysis framework
- Applied log transformation for price normalization

### 2. Feature Engineering
- Implemented one-hot encoding for categorical variables
- Created 235 engineered features from raw data
- Applied standard scaling for feature normalization
- Developed feature selection methodology
- Analyzed feature importance patterns

### 3. Model Development
- Implemented multiple regression models including:
  - Classic ML: Ridge, Lasso, Decision Trees
  - Ensemble Bagging: Random Forest, Extra Trees
  - Ensemble Boosting: XGBoost, CATBoost, Gradient Boosting
- Created comprehensive evaluation framework
- Developed model comparison methodology

### 4. Optimization Framework
- Implemented random search for hyperparameter tuning
- Created cross-validation strategy
- Optimized model parameters for accuracy

### Analysis Features
- Price distribution analysis
- Geographical price patterns
- Feature correlation studies
- Model performance comparisons
- Cross-validation results
- Hyperparameter sensitivity
- Feature importance rankings
- Error distribution analysis
- Neighborhood impact assessment
- Seasonal price variations

## Key Results
1. Achieved 62.87% accuracy on test data with XGBoost
2. Obtained 78.4% accuracy on training data
3. Achieved best RMSE value of 0.42 among all models
4. Successfully processed and analyzed 48,000+ listings
5. Generated 235 meaningful features for prediction
6. Demonstrated superiority of ensemble methods
7. Identified key price-influencing features
8. Established robust cross-validation performance
9. Created comprehensive visualization suite
10. Developed scalable prediction pipeline

## Skills Gained
- Regression model implementation and optimization
- Advanced feature engineering techniques
- Machine learning model evaluation and selection
- Data preprocessing and cleaning
- Statistical analysis and interpretation
- Hyperparameter optimization
- Visualization and reporting
- Large-scale data processing
- Model performance analysis

## Impact
The project provides valuable insights for Airbnb hosts and users in NYC, offering data-driven price prediction capabilities. The methodology can be extended to other real estate markets and pricing scenarios, demonstrating practical applications of machine learning in the hospitality industry. The developed framework serves as a foundation for automated pricing systems and market analysis tools.