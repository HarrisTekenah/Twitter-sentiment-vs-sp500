# Twitter-sentiment-vs-sp500
Exploring the relationship between Twitter sentiment and S&amp;P 500 (SPY) daily returns using VADER sentiment analysis and OLS regression.

# Twitter Sentiment and SPY Stock Movement

This project explores the relationship between Twitter sentiment and daily movements of the S&P 500 ETF (SPY). Using a secondary dataset from Kaggle, it combines textual sentiment analysis with market data to investigate whether public mood on social media can reflect or anticipate short-term stock trends.

## Overview

The analysis employs **VADER (Valence Aware Dictionary and sEntiment Reasoner)** to quantify sentiment polarity from tweets. The sentiment scores are then compared against SPY’s daily percentage changes to uncover potential correlations between investor sentiment and market behavior.

## Key Steps

1. **Data Loading and Cleaning:**  
   Imported and cleaned both tweet and SPY datasets, ensuring synchronized timestamps.

2. **Sentiment Scoring:**  
   Applied VADER sentiment analysis to compute compound sentiment scores for each tweet, then aggregated by day.

3. **Data Merging and Analysis:**  
   Merged daily sentiment averages with SPY returns to explore trends, volatility, and direction.

4. **Visualization:**  
   Produced line charts and scatter plots showing the interaction between sentiment and price movements.

## Results Summary

The findings suggest a mild positive association between public sentiment and SPY’s short-term returns. This aligns with behavioral finance theories indicating that **investor psychology** can influence market prices, even in large, efficient markets.

However, the analysis is limited by the small dataset and reliance on VADER, which may oversimplify financial language. Future enhancements could integrate lagged effects, multi-stock analysis, or news-based sentiment for broader predictive strength.

## Tools and Libraries

- Python  
- pandas, numpy  
- matplotlib, seaborn  
- nltk (VADER)  
- yfinance  

## Limitations

The dataset represents a small time window and focuses on a single stock index (SPY). The use of VADER may not fully capture nuanced financial expressions common in market discussions.

## Future Work

In future iterations, I plan to:
- Incorporate **news sentiment**, **trading volume**, and **volatility measures**  
- Explore **topic-specific sentiment** (e.g., inflation, earnings, tech sector)  
- Apply **machine learning models** for predictive analysis

## Author

**Harris Tekenah**  
Data Science Learner | Mathematics Graduate | MScFE Student at WorldQuant University  
GitHub: [HarrisTekenah](https://github.com/HarrisTekenah)
