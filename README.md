# Quantitative Finance and Investment Analytics Portfolio

Welcome to my Quantitative Finance Portfolio. This repository contains a collection of Python-based models and systematic strategies focused on Asset Management, Risk Modeling, Portfolio Optimization, and Asset Pricing.
All projects are built using real-world financial data (Yahoo Finance, Kenneth French Data Library, OpenML) and industry-standard libraries (`cvxpy`, `PyPortfolioOpt`, `statsmodels`, `scikit-learn`).

---

## Tech stack
* **Language:** Python
* **Optimization & Math:** `cvxpy`, `scipy`, `numpy`
* **Financial Modeling:** `PyPortfolioOpt`, `yfinance`, `pandas_datareader`
* **Data Science & Econometrics:** `pandas`, `statsmodels`, `scikit-learn`, `matplotlib`

---

## Repository structure

### [01_Corporate_Finance_and_Valuation](./01_Corporate_Finance_and_Valuation/)
* **`valuation_monte_carlo.ipynb`**: Engineered a risk-adjusted capital budgeting tool integrating deterministic metrics (NPV, IRR, WACC) with **Monte Carlo simulations** to quantify the probability of loss under cash flow uncertainty.
* **`ddm_fundamental_valuation.ipynb`**: Estimated intrinsic equity value by computing fundamental growth ($g$) via logarithmic regression and required returns using the **Capital Asset Pricing Model (CAPM)**.

### [02_Credit_Risk_Modeling](./02_Credit_Risk_Modeling/)
* **`credit_scoring_pd_lgd.ipynb`**: Developed an end-to-end credit risk framework. Modeled **Probability of Default (PD)** using Logistic Regression (evaluated via Out-of-Sample ROC/AUC) and estimated **Loss Given Default (LGD)** via Linear Regression, analyzing the impact of downturn cycles and collaterals.

### [03_Asset_Pricing_and_Factors](./03_Asset_Pricing_and_Factors/)
* **`fama_french_carhart_models.ipynb`**: Decomposed systematic risk by implementing **Fama-French (3 and 5-factor)** and **Carhart Momentum** models, automating the identification of equity investment styles (Value vs. Growth, Large vs. Small Cap).
* **`active_management_alpha.ipynb`**: Measured portfolio manager skill by isolating **Alpha** and tracking error. Optimized active vs. passive allocations using the **Treynor-Black model** and analyzed levered/unlevered Betas for Capital Structure variations.

### [04_Advanced_Portfolio_Optimization](./04_Advanced_Portfolio_Optimization/)
* **`robust_portfolio_optimization.ipynb`**: Built Mean-Variance optimal portfolios and simulated Efficient Frontiers using `cvxpy`. Enhanced the traditional framework by integrating the **Black-Litterman model** to incorporate subjective investor views and **CVaR minimization** to manage tail risks during extreme downturns.

### [05_Systematic_Trading_Strategies](./05_Systematic_Trading_Strategies/)
* **`etf_allocation_backtest.ipynb`**: Engineered a robust monthly-rebalancing backtesting engine for an ETF portfolio (SPY, QQQ, GLD, TLT, VNQ). Evaluated strategy performance against the S&P 500 using institutional metrics (CAGR, Sharpe, Sortino, Max Drawdown).
* **`factor_momentum_strategy.ipynb`**: Built a systematic *Walk-Forward* algorithm replicating the Cross-Sectional Momentum factor. The model automatically ranks and rebalances top-performing equities monthly without look-ahead bias.
* **`risk_parity_portfolio.ipynb`**: Constructed an institutional-grade Asset Allocation model (inspired by Bridgewater Associates) where each asset class contributes equally to the overall portfolio volatility, optimizing for risk rather than capital weight.

---

## 👨‍💻 About Me
**Ricardo A. Sifuentes Zevallos**
* International Economics student - Universidad Nacional Mayor de San Marcos (UNMSM) | Top 20%
* Specialized in Asset Management, Quantitative Finance, and Data Analytics.
* **Contact:** [szricardo112@gmail.com](mailto:szricardo112@gmail.com) | [LinkedIn Profile](https://www.linkedin.com/in/ricardo-sifuentes-zevallos)

> *“In investing, what is comfortable is rarely profitable.”*
