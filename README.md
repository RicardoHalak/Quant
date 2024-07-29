# Quantitative Finance Projects
**--- NOT FINANCIAL ADVICE ---**

## [Stock Movement Prediction using LSTM](https://colab.research.google.com/drive/1H_Dn58foWjGl6U-fi8yoTpL3z3clVI9R?usp=sharing)
This notebook guides you through using Long Short-Term Memory (LSTM) neural networks to predict stock movements. It starts with an introduction to the core concepts, including what LSTMs are, how they are applied, their advantages and limitations, and their main components. Next, it discusses backtesting, covering its limitations and important metrics like total return, annualized return, annualized standard deviation, drawdown, Sharpe ratio, and win/loss ratio. 

The implementation section walks you through the practical steps: importing libraries -- yfinance, pandas, numpy, matplotlib, seaborn, sklearn, tensorflow.keras --, collecting and preprocessing data, calculating returns, scaling data, creating sequences, and splitting the data into training, validation, and test sets. It also covers building and training the LSTM model using Dropout and Batch Normalization, making returns predictions, and evaluating the accuracy of predictions for upward and downward moves. A simple trading strategy is built based on the LSTM predictions. The notebook concludes conducting a backtest with a thorough evaluation of the performance of the strategy using the metrics mentioned above.

<br>

## [Black-Scholes Model for European Option Pricing](https://colab.research.google.com/drive/1a580QGd6wzIviVfXvYnLDacntJ5-V-uc?usp=sharing)
<br>
This notebook explores the fundamentals of the Black-Scholes option pricing model. It begins with an overview of key concepts, including the Black-Scholes formula and the assumptions underpinning the model. The notebook then delves into the Black-Scholes Greeks, which are essential for understanding how different factors affect options pricing. These Greeks include Delta (Δ), Gamma (Γ), Vega (ν), Theta (Θ), and Rho (ρ). Finally, the notebook includes an example and sanity check to illustrate the practical application of the model and verify its calculations.

## [Calculating Option Implied Volatility using Newton-Raphson Method](https://colab.research.google.com/drive/17bx4AO06UQs0qWrbYsx2LouKfNs_V_ek?usp=sharing)
<br>
This notebook provides a thorough exploration of implied volatility and its significance in financial modeling. It starts with an introduction to the basic concept of volatility and explains why implied volatility is a crucial measure. The notebook then covers how to find implied volatility using the Newton-Raphson method. The notebook outlines the steps involved in the Newton-Raphson method, including its advantages and disadvantages. The process of calculating implied volatility is detailed, with specific focus on the Black-Scholes formula, formulating the problem, and applying the Newton-Raphson iterative formula. The notebook also presents the iterative algorithm used for calculations, culminating in a practical implementation of the method.

## [Calculating VaR and CVaR using Monte Carlo Simulations](https://colab.research.google.com/drive/1aBb-kQydSxyHwIVK63dFNDraU9WALMTN?usp=sharing) 
<br>
This notebook delves into the principles and applications of Monte Carlo simulation. It begins with key concepts and outlines the essential steps involved in running a Monte Carlo simulation. The notebook includes a hands-on example for estimating the value of Pi, accompanied by visualizations to illustrate the simulation process. Expanding on these fundamentals, the notebook applies Monte Carlo methods to stock portfolio analysis, focusing on Value-at-Risk (VaR) and its key components. The notebook also introduces Conditional Value-at-Risk (CVaR) as a complementary risk of VaR assessment tool.

## [Financial Data Analysis and Visualization](https://colab.research.google.com/drive/1JYAsR-_XC_9HAg7yOc9LiiVl9a07-zYQ?usp=sharing)
<br>
This notebook is a simple step-by-step to analyze and visualize financial data. It covers importing necessary libraries -- yfinance, pandas, numpy, matplotlib, seaborn --, collecting stock data from Yahoo Finance, and exploring and cleaning the data. Key metrics such as closing prices, moving averages, trading volumes, and Bollinger Bands are visualized. Additionally, the notebook includes analysis of financial metrics such as daily and cumulative returns and correlation analysis to uncover relationships between different financial indicators.



