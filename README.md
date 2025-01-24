# Doge-Coin-Price-Prediction

# Introduction:
Dogecoin, known for its unique cultural significance, has become a notable cryptocurrency with market behavior driven by historical trends and community activity. This project employs Long Short-Term Memory (LSTM) networks to predict Dogecoin prices using historical market data, addressing the challenges of high volatility in the cryptocurrency market. By analyzing key features such as daily prices and trading volume, the study aims to provide actionable insights for investors and establish a foundation for future research in cryptocurrency forecasting.

# Steps taken:
Project Planning
Literature Review
Data Collection
Data Preprocessing
EDA(Exploratory Data Analysis)
Feature Engineering
Modelling
Final Evaluation

# Project Planning
## Problem Statement:
The cryptocurrency market, particularly Dogecoin, is highly volatile and influenced by numerous factors, making price prediction a complex challenge. Traditional forecasting methods struggle to capture the dynamic and sequential nature of cryptocurrency price fluctuations. This project aims to address these challenges by developing a robust Long Short-Term Memory (LSTM) model to predict Dogecoin prices using historical market data. The objective is to provide accurate price predictions and actionable insights for investors and traders navigating the unpredictable cryptocurrency market.

# Business Needs:
The cryptocurrency market is marked by high volatility, making accurate price prediction crucial for informed decision-making. This project addresses the following business needs:

1. Improved Investment Strategies: Provide accurate Dogecoin price forecasts to assist traders and investors in optimizing their strategies and mitigating risks.
2. Market Insights: Analyze historical price trends and trading volumes to understand market dynamics and identify patterns that influence price fluctuations.
3. Decision Support: Develop a reliable forecasting model to enable timely and data-driven decisions in the rapidly changing cryptocurrency market.
4. Technology Application: Demonstrate the effectiveness of advanced machine learning techniques, specifically LSTM networks, in solving real-world financial forecasting challenges.

# Data Collection
The data contains historical market data for Dogecoin was collected from Investing.com, which included key features such as:

1. Open Price: The price at which Dogecoin began trading each day.
2. Close Price: The price at which trading ended each day.
3. High Price: The maximum trading price recorded during the day.
4. Low Price: The minimum trading price recorded during the day.
5. Volume: The total number of trades conducted during the day.

This comprehensive dataset provided a solid foundation for building the predictive model.

# EDA(Exploratory Data Analysis):
EDA helped uncover key trends and relationships within the dataset:

1. Historical Price Trends: Visualized Dogecoin’s price trajectory from 2017 to 2024, identifying significant spikes, especially in 2021 due to market events and social media buzz.
2. Price Dynamics: Explored how trading volume, high, low, and close prices varied across months and years.
3. Correlation Analysis: Analyzed relationships between variables to understand how market factors like volume and daily price range influenced each other.

Visualizations such as line graphs and heatmaps highlighted the volatility and trends in Dogecoin’s pricing behavior.

# Modelling:
Building on the EDA findings, we applied Long Short-Term Memory (LSTM) networks to predict Dogecoin prices based on historical market data. The model was optimized with key hyperparameters, including learning rate, epochs, and batch size, to achieve high accuracy. Its performance was evaluated using metrics such as RMSE and R² to ensure reliable predictions for cryptocurrency price trends.

1. Logistical Regression:
Mean Squared Error: 7.96734172672608e-06
R – Squared – 0.9991366715285758

2. Random forest classifier:
Mean Absolute Error(MAE): 0.00156090926865671
Residual Sum of Squares(MSE): 4.64456870410277e-05
R2-Score: 0.9949672192592324

3. Long – Short Term Memory:
R2 score: 0.9788214420473016
RMSE: 0.013330799087537063

An LSTM (Long Short-Term Memory) network was chosen for its strengths in handling sequential and time-series data.

1. Architecture: The LSTM model included memory cells and gating mechanisms to capture long-term dependencies in price fluctuations.
2. Hyperparameter Tuning: Key parameters such as optimizer (Adam), learning rate (0.01), batch size (32), and epochs (50) were fine-tuned to achieve the best performance.
3. Training and Testing: The model was trained on a portion of the dataset and tested on unseen data, ensuring robust evaluation.
4. Performance Metrics: The model achieved:
5. RMSE: 0.000651
6. R² Score: 0.894961

These results validated the model’s ability to predict trends accurately, though it faced challenges during extreme price spikes.

# Recommendations:
Based on the findings, the following recommendations were proposed:
1. Enhanced Data Integration: Incorporate social media sentiment and macroeconomic indicators to capture market sentiments and external factors.
2. Hybrid Models: Develop hybrid predictive models combining LSTM with traditional statistical methods for better handling of high volatility.
3. Market Strategies: Use the insights from predictions to guide trading strategies and mitigate risks during volatile periods.
4. Improved Data Sources: Continuously update the model with real-time data for better adaptability to rapid market changes.

# Conclusion:
This study effectively demonstrated the potential of LSTM networks in forecasting cryptocurrency prices using historical data. The model provided strong predictive performance during stable and moderately volatile periods, but its limitations during extreme volatility highlighted the need for expanded feature sets and hybrid approaches. These insights pave the way for future innovations in cryptocurrency market analysis and decision-making tools for investors.
