# Quantitative Finance Projects

## [Long-only Trading Strategy based on Random Forests to Forecast Stock Movements](https://colab.research.google.com/drive/1_QqpvhfTRzi7BVRl8kMlCPM47qMjK_c2?usp=sharing)
---
In this project, we create a long-only trading strategy based on the application of Random Forests to predict stock market trends. The project begins with an introduction to Random Forests, detailing how they operate, their advantages, and limitations. It then delves into the critical aspect of hyperparameter tuning, presenting common hyperparameters tuning techniques like Grid Search, Random Search, and Bayesian Optimization. The section on feature engineering highlights its benefits and provides examples, including feature creation and transformation. The implementation phase involves loading libraries and data, followed by detailed feature engineering techniques such as Relative Strength Index (RSI) and Moving Average Convergence Divergence (MACD). The data is then split into training, validation, and test sets. We establish several baselines, including risk-free rate, buy and hold, random strategy, and S&P 500 index, to benchmark our strategy. After hyperparameter tuning, we backtest our strategy based on the models that provided the highest Sharpe ratio, maximum returns, lowest volatility, and highest accuracy. Finally, the results are presented and compared against the baselines. Additionally, feature importance is presented, showing the contributions of various features to the predictions of the highest return model.
<br>

**Keywords**: Random Forests, Hyperparameters Tuning, Feature Engineering, Relative Strength Index, Moving Average Convergence Divergence, Backtesting Baselines <br>
**Libraries**: yfinance, pandas, numpy, matplotlib, tqdm, sklearn

## [Pairs Trading GOOG-GOOGL](https://colab.research.google.com/drive/1_tW2j2ZyMuuAOcp6oOKhXqXySO42FsgI?usp=sharing)
This notebook provides a comprehensive exploration of pairs trading, a popular statistical arbitrage strategy, focusing on its mathematical foundations, implementation, and optimization. We start with an introduction to pairs trading and its mathematical underpinnings, including the concept of the Z-score and its application in trading strategies. The notebook details a simple process for optimizing exit and entry thresholds to enhance trading performance. We use S&P500 performance as a baseline and proceed with the practical implementation of the strategy. Key steps include the Engle-Granger cointegration test to identify cointegrated pairs and the visualization of optimal exit and entry thresholds. The backtesting section evaluates two different strategies: trading strategy optimized for the highest total return and optimized for highest sharpe ratio. Performance is assessed on both validation and test sets, providing insights into the robustness and effectiveness of the strategies
<br>

**Keywords**: Pairs Trading, Cointegration, Backtesting <br>
**Libraries**: yfinance, pandas, numpy, matplotlib, tqdm, statsmodels

<! --
## [Stock Movement Prediction using LSTM](https://colab.research.google.com/drive/1H_Dn58foWjGl6U-fi8yoTpL3z3clVI9R?usp=sharing)
This notebook guides you through using Long Short-Term Memory (LSTM) neural networks to predict stock movements. It starts with an introduction to the core concepts, including what LSTMs are, how they are applied, their advantages and limitations, and their main components (gates). Next, it introduces the concept of backtesting, covering its limitations and important metrics such as **total return, annualized return, annualized standard deviation, drawdown, sharpe ratio, and win/loss ratio**. 

The implementation section walks you through the practical steps: importing libraries, collecting and preprocessing data, calculating returns, scaling data, creating sequences, and splitting these sequences into training, validation, and test sets. It also covers building and training the LSTM model using Dropout and Batch Normalization, making returns predictions, and evaluating the accuracy of predictions for upward and downward moves. A simple, long-only trading strategy is built based on the LSTM predictions to demonstrate the concept of **backtesting**. The notebook concludes conducting an evaluation of the performance of the strategy using the metrics mentioned above.
<br> 
-->

**Keywords**: Long Short-Term Memory (LSTM) neural networks, Backtesting, Portfolio Metrics, Trading Strategy <br>
**Libraries**: yfinance, pandas, numpy, matplotlib, seaborn, sklearn, tensorflow, tensorflow.keras, random, os

## [Black-Scholes Model for European Option Pricing](https://colab.research.google.com/drive/1a580QGd6wzIviVfXvYnLDacntJ5-V-uc?usp=sharing)
This notebook explores the fundamentals of the **Black-Scholes option pricing model**. It begins with an overview of key concepts, including the Black-Scholes formula and the assumptions underpinning the model. The notebook then delves into the **Black-Scholes Greeks**, which are essential for understanding how different factors affect options pricing. These Greeks include Delta (Δ), Gamma (Γ), Vega (ν), Theta (Θ), and Rho (ρ). Finally, the notebook includes an example and sanity check to illustrate the practical application of the model and verify its calculations. 
<br>

**Keywords**: Black-Scholes Model, Black-Scholes Greeks <br>
**Libraries**: numpy, scipy.stats, py_vollib

## [Calculating Option Implied Volatility using Newton-Raphson Method](https://colab.research.google.com/drive/17bx4AO06UQs0qWrbYsx2LouKfNs_V_ek?usp=sharing)
This notebook provides a thorough exploration of implied volatility and its significance in financial modeling. It starts with an introduction to the basic concept of volatility and explains why implied volatility is a crucial measure. The notebook then covers how to find implied volatility using the Newton-Raphson method. The notebook outlines the steps involved in the Newton-Raphson method, including its advantages and disadvantages. The process of calculating implied volatility is detailed, formulating the problem and applying the Newton-Raphson iterative formula with specific focus on the importance and application of the Black-Scholes formula in this method. The notebook also presents the iterative algorithm used for calculations, culminating in a practical implementation of the method.
<br>

**Keywords**: Implied Volatility, Newton-Raphson Method, Black-Scholes Model <br>
**Libraries**: numpy, scipy.stats

## [Calculating VaR and CVaR using Monte Carlo Simulations](https://colab.research.google.com/drive/1aBb-kQydSxyHwIVK63dFNDraU9WALMTN?usp=sharing) 
This notebook delves into the principles and applications of Monte Carlo simulation. It begins with key concepts and outlines the essential steps involved in running a Monte Carlo simulation. The notebook includes a hands-on example for estimating the value of Pi, accompanied by visualizations to illustrate the simulation process. Expanding on these fundamentals, the notebook applies Monte Carlo methods to stock portfolio analysis, focusing on Value-at-Risk (VaR) and its key components. The notebook also introduces **Conditional Value-at-Risk (CVaR)** as a complementary risk of VaR assessment tool. 

**Keywords**: Monte Carlo Simulations, Value-at-Risk, Conditional Value-at-Risk <br>
**Libraries**: yfinance, pandas, numpy, datetime, random, matplotlib

## [Financial Data Analysis and Visualization](https://colab.research.google.com/drive/1JYAsR-_XC_9HAg7yOc9LiiVl9a07-zYQ?usp=sharing)
This notebook is a simple step-by-step to analyze and visualize financial data. It covers importing necessary libraries, collecting stock data from Yahoo Finance, and exploring and cleaning the data. Key metrics such as closing prices, moving averages, trading volumes, and Bollinger Bands are visualized. Additionally, the notebook includes analysis of financial metrics such as daily and cumulative returns and correlation analysis to uncover relationships between different financial indicators.
<br>

**Keywords**: Data Visualization, Financial Metrics <br>
**Libraries**: yfinance, pandas, numpy, matplotlib, seaborn

## [XGBoost]()
---
<br>

## [PCA]()
---
<br>

## [ARIMA]()
---
<br>

## [GARCH]()
---
<br>

