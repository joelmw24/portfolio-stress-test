# Stress testing & risk validation on multi-asset portfolios

<img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue}" /> <img src="https://img.shields.io/badge/VSCode-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white" />

Finance project focused on **portfolio risk analysis and
stress testing** using historical market data.

This project evaluates how a portfolio behaves under normal market
conditions and during extreme crisis periods.

> ⚠️ This project is for academic and educational purposes only

------------------------------------------------------------------------

## Project objectives

-   Construct and clean financial time series data
-   Compute portfolio returns
-   Measure key risk metrics
-   Perform historical stress testing
-   Analyze portfolio performance during crisis windows

------------------------------------------------------------------------

## Data & methodology


------------------------------------------------------------------------

## Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Jupyter Notebook**

------------------------------------------------------------------------

## Repository structure

```
portfolio-stress-test/
│
├── data/
│   ├── portfolio_returns_log.csv       # portfolio-level log returns
│   ├── prices.csv                      # raw asset prices
│   ├── returns_log.csv                 # asset-level log returns
│   ├── risk_metrics.csv                
│   └── weights.csv                     
│
├── 01_Data_and_portfolio.ipynb         # data collection and portfolio construction
├── 02_Risk_metrics.ipynb               # risk indicators computation
├── 03_Historical_stress_testing.ipynb  # historical crisis scenario analysis
├── 04_Market_stock_stress_testing.ipynb # market shock stress scenarios
├── 05_Metrics_comparison.ipynb         # cross-scenario metrics comparison
│
├── .gitignore
├── LICENSE
└── README.md

```

------------------------------------------------------------------------

## How to run
1. Clone the repository:
```bash
git clone https://github.com/joelmw24/portfolio-stress-test.git
cd portfolio-stress-test
```

2. Install dependencies:
```bash
pip install pandas numpy matplotlib jupyter

3. Run the notebooks in order:
```bash
jupyter notebook
```

------------------------------------------------------------------------

## Possible Extensions

-   **Monte Carlo simulations**
-   **Multi-factor stress scenarios**
-   **Portfolio optimization**
-   **Dynamic risk monitoring**

------------------------------------------------------------------------

## Author

**Joël Mwemba**  
Engineering student
