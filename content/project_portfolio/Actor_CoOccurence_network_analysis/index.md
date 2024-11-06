---
title: 'Actor Co-occurrence Network Link Prediction'
date: 2023-03-10
tags: [
    "Graph Theory",
    "Machine Learning",
    "Data Mining",
    "Social Network Analysis",
    "Data Analysis"
]
image: 'cover.png'
github: 'https://github.com/Jvanshika11/Actor_co-occurence-network_Link-prediction'
draft: false
---

Developed a sophisticated link prediction system for actor co-occurrence networks using advanced machine learning techniques, achieving 76.42% prediction accuracy with logistic regression. The project successfully combined graph structural features with node attributes to predict missing edges in the network, demonstrating superior performance across multiple evaluation metrics including F1 score (0.7607) and AUC score.

<!--more-->

## Overview
The project tackles the challenge of link prediction in actor co-occurrence networks derived from Wikipedia pages. By leveraging both graph structure and node attributes, the system predicts potential connections between actors who might appear together. Through comprehensive experimentation with various machine learning models and feature engineering techniques, the project demonstrates the effectiveness of combining traditional machine learning with graph-based features for network analysis tasks.

## Technologies
- **Programming**: Python, Jupyter Notebooks
- **Graph Processing**: NetworkX, Graph-tool
- **Machine Learning**: Scikit-learn, XGBoost, Random Forest
- **Data Processing**: NumPy, Pandas, SciPy
- **Visualization**: Matplotlib, Seaborn, NetworkX plotting
- **Model Evaluation**: Scikit-learn metrics
- **Statistical Analysis**: StatsModels
- **Graph Algorithms**: PageRank, Random Walk

## Implementation Details

### 1. Graph Construction and Feature Engineering
- Built directed graph structure from 10k node pairs using NetworkX
- Implemented PageRank algorithm with alpha parameter 0.8
- Generated node-level features including degree centrality and clustering coefficients
- Developed random walk similarity measurements
- Created comprehensive feature vectors for edge prediction

### 2. Model Development
- Implemented multiple machine learning models for comparison
- Developed feature scaling and preprocessing pipeline
- Created training/validation split methodology
- Implemented model evaluation framework

### 3. Performance Optimization
- Fine-tuned model parameters for optimal performance for each model
- Optimized memory usage for large graph processing

### 4. Evaluation Framework
- Created comprehensive model comparison metrics
- Implemented cross-validation methodology
- Developed performance visualization tools
- Established baseline measurements

### Analysis Features
- Graph structural analysis
- Node centrality measurements
- Random walk similarity computations
- Model performance comparisons
- Feature importance analysis
- Network visualization
- Prediction probability distribution
- Cross-validation performance
- Error analysis visualization
- Scalability assessment

## Key Results
- Achieved 76.42% accuracy with logistic regression classifier
- Obtained F1 score of 0.7607, outperforming other models
- Demonstrated superior AUC score compared to baseline models
- Successfully processed and analyzed 10k node pairs
- Identified key structural features for link prediction
- Optimized PageRank parameters for network analysis
- Validated model performance through cross-validation
- Identified optimal hyperparameters for each model type

## Skills Gained
- Network science and graph theory applications
- Machine learning model implementation and optimization
- Feature engineering for graph data
- Performance metrics analysis and interpretation
- Large-scale graph processing
- Model comparison and selection
- Data preprocessing and cleaning
- Scientific visualization

## Impact
The project demonstrates practical applications of machine learning in network analysis, particularly valuable for recommendation systems and network reconstruction. The methodology can be extended to various types of social and professional networks, offering insights into relationship prediction and network evolution. The developed framework provides a foundation for future work in link prediction across different domains.