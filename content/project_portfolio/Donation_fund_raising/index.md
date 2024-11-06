---
title: 'Donation Campaign Analysis and Revenue Prediction'
date: 2022-11-15
tags: [
    "Data Analysis",
    "Machine Learning",
    "Regression Analysis",
    "Financial Analysis"
]
image: 'cover.png'
github: 'https://github.com/Jvanshika11/Donation-fundraising-campaign_analysis_and_revenue-predictions'
draft: false
---

Developed a sophisticated predictive analytics system for charity fundraising campaign "SJ22", analysing donation patterns of 79,469 donors to optimise solicitation strategies. The project utilised advanced statistical modelling to predict donation likelihood and amounts, enabling data-driven decisions for maximising campaign profitability through targeted solicitation.

<!--more-->

## Overview
The project addresses the critical challenge of optimising fundraising campaign efficiency by predicting both donation probability and expected amounts. Through comprehensive analysis of donor behaviour and advanced statistical modelling, the system provides recommendations for donor solicitation based on expected revenue against fixed solicitation costs (€2.00). The research focused on developing a robust prediction framework that combines probability and amount predictions to maximise campaign financial performance.

## Technologies
- **Programming**: R, RStudio
- **Database**: MySQL, RODBC
- **Statistical Analysis**: nnet, stats
- **Data Processing**: dplyr, tidyr
- **Machine Learning**: caret
- **Cross-validation**: boot
- **Data Visualisation**: ggplot2
- **Database Connectivity**: DBI
- **Performance Metrics**: ROCR

## Implementation Details

### 1. Data Extraction and Processing
- Developed MySQL database queries for donor information retrieval
- Implemented feature engineering for recency, frequency, and monetary metrics
- Created data cleaning and standardisation pipeline
- Established efficient data partitioning mechanism
- Developed comprehensive donor profiling system

### 2. Model Development
- Implemented multinomial logistic regression for donation probability
- Developed linear regression model for amount prediction
- Created cross-validation framework for model validation
- Implemented feature selection methodology
- Developed model evaluation metrics

### 3. Prediction Framework
- Created integrated prediction system combining probability and amount models
- Implemented ROI-based decision framework
- Developed confidence interval calculations
- Created prediction validation system
- Implemented efficient prediction storage

### 4. Performance Analysis
- Developed comprehensive evaluation metrics
- Created ROI analysis framework
- Implemented model comparison methodology
- Developed visualisation tools for results
- Created prediction accuracy assessment tools

### Analysis Features
- Donor behaviour analysis
- Temporal donation patterns
- ROI calculations per donor
- Model performance metrics
- Cross-validation results
- Probability distribution analysis
- Amount prediction accuracy
- Cost-benefit analysis
- Donor segmentation
- Campaign performance projections

## Key Results
- Analysed donation patterns of 79,469 donors
- Created accurate prediction models for both donation probability and amounts
- Established robust cross-validation framework
- Developed comprehensive ROI analysis system and cost-effective solicitation recommendations
- Created scalable prediction pipeline and automated decision-making framework

## Skills Gained
- Statistical modelling and analysis
- Database management and querying
- Predictive analytics implementation
- ROI analysis and optimisation
- Machine learning model development
- Cross-validation techniques
- Data preprocessing and cleaning
- Performance metrics analysis
- Financial analytics

## Impact
The system provides charities with data-driven decision-making capabilities for fundraising campaigns, enabling efficient resource allocation and increased campaign profitability. The methodology can be adapted for various fundraising scenarios and different charitable organisations, offering a scalable solution for optimising donation campaigns through predictive analytics.