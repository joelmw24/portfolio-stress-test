# 📊 Portfolio Stress Test

Quantitative finance project focused on **portfolio risk analysis and
stress testing** using historical market data.

This project evaluates how a portfolio behaves under normal market
conditions and during extreme crisis periods (e.g., COVID-19 shock).

------------------------------------------------------------------------

## 🎯 Project Objectives

-   Construct and clean financial time series data\
-   Compute portfolio returns\
-   Measure key risk metrics\
-   Perform historical stress testing\
-   Analyze portfolio performance during crisis windows

------------------------------------------------------------------------

## 📁 Project Structure

portfolio-stress-test/ │ ├── data/ \# Market & portfolio data │ ├──
Data_and_portfolio.ipynb \# Data preparation & portfolio construction
├── Risk_metrics.ipynb \# Volatility, VaR, CVaR, Drawdown analysis ├──
Stress_testing.ipynb \# Historical stress scenario analysis │ ├── Votre
profil d'investisseur \| AMF.pdf └── README.md

------------------------------------------------------------------------

## 📌 Notebooks Overview

### 1️⃣ Data_and_portfolio.ipynb

-   Data import and preprocessing\
-   Portfolio construction\
-   Return computation

### 2️⃣ Risk_metrics.ipynb

-   Annualized volatility\
-   Value at Risk (VaR)\
-   Conditional Value at Risk (CVaR)\
-   Maximum Drawdown\
-   Cumulative returns

### 3️⃣ Stress_testing.ipynb

-   Historical scenario analysis\
-   Focus on COVID crisis window\
-   Portfolio cumulative return during stress periods

------------------------------------------------------------------------

## 📈 Example: Historical Stress Window

``` python
covid_portfolio = portfolio.loc[START:END].dropna()
cum_return = (1 + p_s).prod() - 1
```

This allows measurement of portfolio performance over a defined crisis
period.

------------------------------------------------------------------------

## 🛠️ Technologies Used

-   Python\
-   Pandas\
-   NumPy\
-   Matplotlib\
-   Jupyter Notebook

------------------------------------------------------------------------

## 📊 Key Concepts Covered

-   Time series analysis\
-   Portfolio return aggregation\
-   Risk decomposition\
-   Historical stress testing\
-   Tail risk measurement

------------------------------------------------------------------------

## 🚀 Possible Extensions

-   Monte Carlo simulations\
-   Multi-factor stress scenarios\
-   Portfolio optimization\
-   Automated risk reporting

------------------------------------------------------------------------

## 👤 Author

Joel
