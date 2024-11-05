---
title: 'US-Stock-Market-Analysis'
date: 2023-05-15
tags: ["Machine Learning", "Data Analysis", "Graph Theory", "Fintech"]
image: 'cover.png'
github: 'https://github.com/shubham777/US-Stock-Market-Analysis-using-Network-Graphs'
draft: false
---

Developed a sophisticated network analysis system for S&P 500 stocks (2018-2022), employing advanced graph theory and machine learning techniques to visualize and analyze market interconnectivity patterns. The project revealed crucial insights into stock market behavior during the COVID-19 pandemic, identifying influential stocks and sector-based communities through correlation analysis and network metrics. Notable findings included the detection of scale-free properties in market networks and the quantification of sector-based trading patterns using Jaccard similarity coefficients.

<!--more-->

## Overview
The project investigated stock market connectivity patterns using advanced graph theory, a sophisticated network analysis and the Winner-Take-All (WTA) methodology, examining S&P 500 stocks from 2018 to 2022, with a particular focus on the COVID-19 pandemic period. The research answered critical questions about network properties like degree distribution, clustering coefficients, and modularity over time, while also tracking the evolution of stock connectivity during market turbulence. Of particular significance was the identification of high-centrality stocks and their role changes during the pandemic, offering valuable insights for investment strategies and risk management.

## Technologies
- **Programming**: Python
- **Data Processing**: NumPy, Pandas
- **Data Collection**: Yahoo Finance API
- **Visualization**: Matplotlib, Plotly
- **Network Analysis**: NetworkX
- **Machine Learning**: Scikit-learn, Community Detection (Louvain)

## Implementation Details

### 1. Data Collection & Preprocessing
- Implemented web scraping using Python's BeautifulSoup to extract S&P 500 company list from Wikipedia
- Developed automated data collection pipeline using Yahoo Finance API
- Handled missing values through forward-fill and backward-fill methods
- Synchronized trading dates across all stocks

### 2. Data Detrending
- Calculated descriptive statistics for returns distribution
- Computed daily log price returns to eliminate market trends and reduce false correlations: ln(P_t) - ln(P_t-1)
- Applied rolling window calculations for return normalization
- Implemented moving average subtraction for local trend removal
- Validated detrending effectiveness through statistical tests and visualizations
    
### 3. Correlation Analysis
- Developed sliding window mechanism for correlation calculation
- Tested multiple window sizes: 21, 42, 63, 84, and 105 days
- Implemented Pearson correlation coefficient calculations
- Developed visualizations for correlation patterns

### 4. Network Construction
- Applied Winner-Take-All (WTA) methodology with adaptive threshold selection
- Constructed NetworkX graphs with weighted edges based on correlation strength
- Implemented Louvain algorithm for community detection
- Developed metrics for community stability analysis and created visualizations for community structure
- Computed centrality measures (degree, betweenness, closeness)
- Developed temporal analysis framework for tracking network evolution
  
### Analysis Features
- Scale-free property analysis through log-log degree distribution
- Temporal evolution tracking of average network degree
- High-degree and high-betweenness centrality stock identification
- Community structure detection and evolution analysis
- Sector-based correlation using Jaccard similarity coefficients
- Network visualization with weighted edges
- COVID-19 impact analysis on network topology
- Market volatility assessment through network metrics
- Cross-sector connectivity patterns
- Temporal community stability analysis

## Key Results
1. Identified financial sector stocks as consistently high-degree nodes
2. Mapped dramatic network structure changes during March 2020 market crash
3. Discovered strong community correlation in Finance, Real Estate, Utilities, and Energy sectors
4. Quantified weaker community patterns in IT, Materials, and Consumer sectors
5. Demonstrated increased market connectivity during high volatility periods
6. Revealed temporal evolution of stock communities
7. Identified key stocks with high betweenness centrality as potential market indicators
8. Documented significant changes in average network degree during market stress
9. Mapped sector-specific responses to COVID-19 market conditions
10. Established correlation between network metrics and market volatility

## Skills Gained
- Complex network analysis and financial modeling
- Large-scale data processing and optimization
- Advanced Python programming and API integration
- Statistical analysis and machine learning applications
- Graph theory and community detection algorithms
- Financial time series analysis and visualization

## Impact
The system provides actionable insights for investment strategies and risk management, demonstrating the power of network analysis in understanding stock market dynamics. The methodology is adaptable to various market conditions and timeframes, making it a valuable tool for financial analysis.
