# Sankar Ganesh Mutharasan

### Quantitative Finance | Model Risk | Volatility & Derivatives

I conduct empirical research in quantitative finance, focusing on derivatives, volatility forecasting, statistical arbitrage, and financial risk. My projects combine Python, R, statistical modelling, and financial analysis to evaluate competing models, test trading strategies, and examine how financial models behave under changing market conditions.

I am completing an MSc in Financial Analytics at Queen’s University Belfast(GIFT City Campus, India) and pursuing an MSc in Financial Engineering at WorldQuant University(Online). My research interests include quantitative model validation, volatility modelling, derivatives pricing, stochastic modelling, and systematic trading strategies.
  
**Email:** [sankarganesh2021@gmail.com](mailto:sankarganesh2021@gmail.com)  
**LinkedIn:** [linkedin.com/in/sankar-ganesh-m](https://www.linkedin.com/in/sankar-ganesh-m/)  
**GitHub:** [SankarGanesh01](https://github.com/SankarGanesh01)

---

## Selected Research Projects

### 1. IL&FS Default and Indian Index Options Analysis

**Tools:** Python, Black–Scholes, Implied Volatility, Option Greeks, Statistical Testing, Event Study, OLS Regression

Investigated how the 4 September 2018 IL&FS default affected option pricing, implied volatility, and delta-hedging performance in NIFTY and BANKNIFTY index options.

Analysed **248,227 option observations** from June–December 2018 using option valuation, event-period comparisons, statistical tests, and heteroskedasticity-robust regression.

**Key findings**
- Mean absolute pricing error increased from 36.70 before the event to 52.85 after it.
- Implied volatility increased significantly in both indices.
- Absolute delta-hedging errors increased, while variance-based hedge effectiveness remained above 0.90 across most sub-periods.
- BANKNIFTY experienced a stronger deterioration in pricing and hedging measures than NIFTY.

**Limitation:** The event-specific design, constant-volatility assumptions, and discrete hedging approach cannot fully capture changing market conditions and real-world execution frictions.

[**View repository →**](https://github.com/SankarGanesh01/ilfs-index-options-analysis)

### 2. NIFTY 50 Realized Volatility Forecasting

**Tools:** R, Python for data acquisition, ARIMAX, Random Forest, Forecast Evaluation

Developed a one-day-ahead realized-volatility forecasting pipeline using the Garman–Klass estimator and market indicators derived from a liquidity-filtered NSE universe.

The dataset covered 18 October 2007 to 29 July 2026, with training data through 2022, validation during 2023–2024, and an out-of-sample test period from January 2025 to July 2026.

**Key findings**
- ARIMAX achieved the best performance across 388 test observations, with RMSE of approximately 3.54 × 10⁻⁵, MAE of 2.60 × 10⁻⁵, and QLIKE of 0.3209.
- It outperformed Random Forest, naïve random-walk, and historical-mean benchmarks across all three reported metrics.

**Limitation:** Results depend on the volatility proxy, predictor construction, and stock-universe coverage. Historical ticker availability and the liquidity filter require careful consideration when assessing survivorship bias and generalisation.

[**View repository →**](https://github.com/SankarGanesh01/nifty50-realized-volatility-forecasting)

### 3. Machine Learning vs Traditional Pair Selection in Statistical Arbitrage

*Dissertation research — Multimedia University MBA pathway*

**Tools:** Python, PCA, OPTICS Clustering, Cointegration, Rolling Hedge Ratios, Backtesting

Developed a pairs-trading framework across NIFTY 500 and S&P 500 universes. The methodology combines PCA-based factor neutralisation, density-based clustering, cointegration testing, rolling hedge ratios, z-score trading rules, transaction costs, and position-sizing controls.

Evaluated traditional and machine-learning-based pair-selection approaches across different market universes and historical periods.

**Key finding**

In the NIFTY long-period cohort, the traditional strategy achieved a Sharpe ratio of **0.913**, compared with **0.367** for the machine-learning strategy. Added model complexity did not improve risk-adjusted performance in this setting.

**Limitation:** Results depend on universe construction, survivorship and look-ahead bias controls, parameter choices, and execution assumptions. Performance should be interpreted within each cohort's specific backtesting framework.

[**View repository →**](https://github.com/SankarGanesh01/machine-learning-statistical-arbitrage)

### 4. ICICI Bank Foreign-Exchange Exposure and Market Risk

**Tools:** R, Financial Econometrics, Regression Analysis, Structural Break Testing, Time Series

Examined ICICI Bank's equity-return sensitivity to six currencies — USD, GBP, EUR, AED, CNY, and JPY — from January 2019 to April 2026. Compared alternative market-model specifications and assessed changes in currency sensitivities around the COVID-19 period.

**Key findings**
- Estimated market beta was approximately 1.23 across the main specifications.
- Most currency coefficients were economically modest and statistically insignificant in the Western exposure model; the Asian model showed a marginally significant negative JPY coefficient.
- Replacing NIFTY 50 with NIFTY Bank increased model R² to 0.768, highlighting the importance of sector-specific market movements.

**Limitation:** The capital-market approach estimates relationships between currency movements and equity returns. It does not directly measure the bank's balance-sheet FX positions or establish causal effects.

[**View repository →**](https://github.com/SankarGanesh01/icici-bank-fx-exposure-analysis)

### 5. NSE Announcement Sentiment During the IL&FS Credit Crisis

**Tools:** Python, FinBERT, Loughran–McDonald, Event Study, Regression Analysis

Analysed corporate announcements from ten Indian financial firms — five banks and five NBFCs — around the IL&FS credit crisis. Combined financial-text sentiment measures with cumulative abnormal returns, OLS regression, fixed effects, and cluster-robust standard errors.

Identified and corrected a disclosure-filtering issue arising from NSE announcement-subject categorisation, improving the coverage of credit-risk announcements in the event sample.

**Research question:** Does the tone of corporate announcements contain useful information about market reactions during a financial-stress event?

**Limitation:** The sample covers ten firms and one crisis period. Sentiment measures and event-study estimates alone cannot establish that announcement tone causes market movements.

[**View repository →**](https://github.com/SankarGanesh01/nse-announcements-finbert-event-study)

### 6. ASML Equity Valuation Model

**Tools:** Excel, FCFF Discounted Cash Flow, Comparable-Company Valuation, CAPM, Scenario Analysis

Built an Excel-based valuation of ASML Holding N.V. using March 2026 as the valuation date. Combined a free-cash-flow-to-firm DCF model, comparable-company valuation, CAPM-based cost of equity, and scenario analysis to examine intrinsic value under different assumptions.

**Limitation:** Valuation estimates are sensitive to operating forecasts, discount rates, terminal-value assumptions, peer selection, and the financial information available at the valuation date.

[**View repository →**](https://github.com/SankarGanesh01/asml-equity-valuation-model)

---

## Technical Skills

- **Programming:** Python, R, SQL
- **Python Libraries:** NumPy, pandas, scikit-learn
- **Quantitative Methods:** Statistical inference, hypothesis testing, regression analysis, financial time series, cointegration testing, event studies, model evaluation, and backtesting
- **Derivatives & Risk:** Options pricing, implied volatility, option Greeks, delta hedging, market-risk analysis, and model-risk assessment
- **Financial Modelling:** FCFF DCF, comparable-company valuation, financial statement analysis, and scenario analysis
- **Data & Visualisation:** Microsoft Excel, Power BI, Tableau

## Mathematical & Statistical Foundations

- **Probability and Statistics:** Probability distributions, statistical inference, hypothesis testing, estimation, and diagnostic testing
- **Linear Algebra:** Matrix operations, eigenvalues, eigenvectors, covariance matrices, and principal component analysis
- **Calculus & Optimisation:** Differentiation, partial derivatives, constrained optimisation, and numerical methods
- **Stochastic Processes:** Random walks, Brownian motion, and stochastic-process foundations
- **Econometrics:** Stationarity, autocorrelation, time-series modelling, and regression diagnostics

## Relevant Coursework

**MSc Financial Analytics — Queen’s University Belfast**

- **Derivatives:** Black–Scholes pricing, CRR binomial trees, Itô’s lemma, Euler–Maruyama simulation, and delta hedging
- **Advanced Financial Data Analytics:** Stationarity, ARMA/ARIMA, GARCH-family models, Ljung–Box and ARCH-LM diagnostics, and VAR models
- **AI & Trading:** Covariance denoising, the Marčenko–Pastur threshold, Ledoit–Wolf shrinkage, clustering, and portfolio optimisation
- **Financial Modelling in Python:** Numerical implementation of financial models
- **Asset Pricing:** CAPM, beta, risk–return relationships, and valuation

## Education

**MSc Financial Analytics**  
Queen’s University Belfast — GIFT City Campus, India  
Expected completion: January 2027

**MSc Financial Engineering (Online)**  
WorldQuant University  
Expected completion: October 2028

**Master of Business Administration — MBA pathway**  
Multimedia University, Malaysia  
August 2025 – May 2026  
*Undertaken alongside the PGDM programme.*

**PGDM, Finance & Business Analytics**  
Firebird Institute of Research in Management, Coimbatore  
August 2024 – May 2026

**BSc Information Technology**  
Sri Ramakrishna Arts and Science College, Coimbatore  
2020 – 2023

## Experience

**Equity Research Analyst Intern — Arihant Capital Markets Ltd.**  
June 2025 – August 2025

- Conducted company and sector research and financial analysis across seven listed companies.
- Applied discounted cash flow, comparable-company valuation, and financial-ratio analysis to evaluate business performance and investment considerations.

## Certifications

- Artificial Intelligence for Investment — IIT Kanpur (NPTEL)
- AI & ML Applications to Finance — GIFT International Fintech Institute

---

*This portfolio presents research findings within their respective datasets, modelling assumptions, and evaluation periods. Historical results do not imply future investment performance.*
