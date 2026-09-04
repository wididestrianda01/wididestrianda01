<h1 align="center">Widi Destrianda</h1>

<p align="center">
  <strong>Quantitative Finance</strong> · Risk Analytics · Financial Data Science
</p>

<p align="center">
  <img src="https://img.shields.io/badge/MSc%20Financial%20Mathematics-KTH%20%E2%80%94%20May%202027-blue" alt="MSc Financial Mathematics — KTH" />
  <img src="https://img.shields.io/badge/Location-Stockholm%2C%20Sweden-lightgrey" alt="Location: Stockholm, Sweden" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB" alt="Python" />
  <img src="https://img.shields.io/badge/R-276DC3" alt="R" />
  <img src="https://img.shields.io/badge/MATLAB-0076A8" alt="MATLAB" />
  <img src="https://img.shields.io/badge/SQL-4479A1" alt="SQL" />
</p>

```text
$ whoami → engineer turned quant — MSc Financial Mathematics @ KTH, 2027
```

---

## About

Final-year **MSc in Applied and Computational Mathematics** (specialisation in Financial Mathematics) at KTH, Stockholm, graduating **Summer 2027**. I build and backtest quantitative models in Python and R for market risk, credit risk, and energy markets, and I publish the code on GitHub.

I came to finance after seven years in engineering and cost estimation. That work wasn't directly in finance, but the skills transfer: Monte Carlo simulation, regression modelling, forecasting, and making decisions from data. Those are the skills I still reach for in my quantitative work.

## What I'm targeting

Graduate roles in:

- **Risk Analytics** — market risk (VaR / Expected Shortfall), credit risk (IRB PD/LGD/EAD)
- **Portfolio Management**
- **Financial Data Science**
- **Quantitative Analysis**

Open to graduate positions, internships, and master thesis projects from 2027.

## Skills

**Programming** — Python (pandas, NumPy, scikit-learn, statsmodels, XGBoost/CatBoost/LightGBM, SHAP, FastAPI, Streamlit, DuckDB, QuantLib, pytest) · R · SQL · MATLAB · VBA

**Quantitative methods** — time series (ARIMA/SARIMA, GARCH/EGARCH, Prophet, LightGBM) · GLM · high-dimensional regression (Ridge, Lasso, PCR, PLS) · DCC-GARCH and copulas · Monte Carlo and discrete-event simulation

**Financial & risk modelling** — Basel III IRB (PD/LGD/EAD) · VaR and Expected Shortfall · Kupiec and Christoffersen backtesting · credit scorecards · insurance pricing · stochastic calculus

**Tools** — Docker · Tableau · Advanced Excel · Git/GitHub · Claude Code agent workflows

## Projects by topic area

### Market & Credit Risk

| Project | Description | Stack |
| --- | --- | --- |
| [credit-risk-model-validation-workbench](https://github.com/wididestrianda01/credit-risk-model-validation-workbench) | Regulatory credit-risk & model-validation workbench: IFRS 9 expected-credit-loss pipeline and independent validation over a frozen Freddie Mac cohort — PD/LGD/EAD, staging, six-effect reconciliation, governance, monitoring, and a causal/fairness analysis. 35 modules, 190 tests, `mypy --strict` clean. | Python |
| [aml-workbench](https://github.com/wididestrianda01/aml-workbench) | AML transaction-monitoring workbench on public data (Elliptic + IBM HI-Small): rule-based scenario engine, graph features, and a GNN/GBM challenger under strict-inductive temporal walk-forward validation (PR-AUC 0.907), with PSI drift monitoring, precision@k alert economics, and a Streamlit triage console. | Python |
| [nordic-power-market-risk](https://github.com/wididestrianda01/nordic-power-market-risk) | Decision and risk system for a battery in the Swedish SE3 zone: MILP dispatch of energy and reserve capacity (FCR/aFRR/mFRR) across day-ahead, imbalance, and reserve markets, gated on CVaR and drawdown tail-risk limits and settled against observed prices. Probabilistic quantile forecasting (LEAR) drives the optimizer, with a walk-forward P&L netting EUR 483,956 versus EUR 86,516 for a heuristic benchmark. | Python, Docker |
| [credit-risk-pipeline](https://github.com/wididestrianda01/credit-risk-pipeline) | Basel III IRB credit scoring pipeline: CatBoost, XGBoost, and LightGBM PD models with 0.58 out-of-time Gini, SHAP explanations for adverse action, served through FastAPI and Streamlit. | Python |
| [lgd-ead-irb-modelling](https://github.com/wididestrianda01/lgd-ead-irb-modelling) | IRB LGD and EAD capital models for Fannie Mae mortgages, aligned with CRR/EBA requirements, with a live Streamlit validation dashboard. | Python |
| [var-es-risk-engine](https://github.com/wididestrianda01/var-es-risk-engine) | FRTB-aligned VaR and Expected Shortfall engine: GARCH volatility, Kupiec and Christoffersen backtesting, and a Streamlit dashboard for risk reporting. | Python |

### Derivatives & Mathematical Finance

| Project | Description | Stack |
| --- | --- | --- |
| [pricing-model-validation](https://github.com/wididestrianda01/pricing-model-validation) | Numerical derivatives-pricing and model-validation core: Monte Carlo, finite-difference PDEs, Greeks, and SABR/Heston calibration, each challenged against closed forms and QuantLib, with an SR 26-2-style validation report. | Python |
| [fixed-income-curve-engine](https://github.com/wididestrianda01/fixed-income-curve-engine) | Yield-curve construction and fixed-income pricing built from scratch in Python, cross-checked against QuantLib. Term-structure models (Hull-White, G2++), SABR volatility smiles, Svensson calibration, and interest-rate risk: DV01, duration and convexity, key-rate duration, and delta VaR/ES. | Python |
| [Option_Pricing](https://github.com/wididestrianda01/Option_Pricing) | Black-Scholes pricing and Greeks from first principles: analytical and finite-difference Greeks, implied-volatility inversion, a volatility surface, CRR binomial cross-check, American early-exercise premium, and delta-hedging P&L, calibrated to OMXS30. | Python |
| [Continuous-Time-Markov-Chains](https://github.com/wididestrianda01/Continuous-Time-Markov-Chains) | Continuous-time Markov chain model of ferry reliability under competing maintenance strategies, validated by two independent simulation approaches. | MATLAB |

### Energy & Commodity Markets

| Project | Description | Stack |
| --- | --- | --- |
| [cross-commodity-energy-trading](https://github.com/wididestrianda01/cross-commodity-energy-trading) | Spread economics, DCC-GARCH correlation, and t-copula VaR across Brent, TTF gas, EUA carbon, and European power, to measure portfolio tail risk and cross-commodity spreads. | Python |
| [nordic-electricity-forecasting](https://github.com/wididestrianda01/nordic-electricity-forecasting) | Day-ahead Nord Pool price forecasting with a ten-model comparison, ranked on an accuracy-versus-compute Pareto frontier. Compares gradient-boosted trees, foundation, deep, and classical models with leakage-free features, expanding-window backtests, CRPS and pinball scoring, and Diebold–Mariano tests. | Python |
| [Austrian-Daily-Electricity-Load-Forecast](https://github.com/wididestrianda01/Austrian-Daily-Electricity-Load-Forecast) | ARMA modelling and a 31-day out-of-sample forecast of Austrian electricity load, with model diagnostics and forecast evaluation. | Python |
| [freq-anomaly-detection](https://github.com/wididestrianda01/freq-anomaly-detection) | Rolling z-score and CUSUM anomaly detection on Nordic grid frequency, validated against ENTSO-E outage records. | Python |
| [nordic-spot-price-forecasting](https://github.com/wididestrianda01/nordic-spot-price-forecasting) | Day-ahead SE3 spot price forecasting with SARIMA, Prophet, and LightGBM, evaluated out-of-sample on a common test year with spike-separated MAE/RMSE. | Python |

### Statistical & Machine Learning Modelling

| Project | Description | Stack |
| --- | --- | --- |
| [google-stock-volatility-forecasting](https://github.com/wididestrianda01/google-stock-volatility-forecasting) | ARMA mean dynamics plus GARCH volatility clustering on Google stock returns, with volatility forecasts and residual diagnostics. | Python |
| [project-2-glm-insurance-pricing](https://github.com/wididestrianda01/project-2-glm-insurance-pricing) | Multiplicative Poisson and Gamma GLMs for pure-premium insurance pricing, with model selection and rate relativities. | Python |
| [project-1-high-dimensional-regression](https://github.com/wididestrianda01/project-1-high-dimensional-regression) | PCR, PLS, Ridge, and Lasso with multi-split inference on a 4,088-predictor genomics dataset, comparing shrinkage methods on prediction error. | R |
| [spare-parts-optimization](https://github.com/wididestrianda01/spare-parts-optimization) | Minimises expected backorders under a budget constraint using marginal allocation and dynamic programming. | MATLAB |
| [Instacart](https://github.com/wididestrianda01/Instacart) | Customer segmentation and market-basket analysis on Instacart orders, with clustering and association rules. | Python |
| [Customer-Analytics-Preparing-Data-for-Modelling](https://github.com/wididestrianda01/Customer-Analytics-Preparing-Data-for-Modelling) | Cleaning, feature engineering, and validation of messy customer data for modelling. | Python |
| [lime-equity-research](https://github.com/wididestrianda01/lime-equity-research) | Equity research note on Lime Technologies AB (LIME.ST): two-stage DCF, WACC build, Nordic SaaS comparables, and a HOLD recommendation. | Python |

### Foundations

Early data-science work: [Exploring-Airbnb-Market-Trends](https://github.com/wididestrianda01/Exploring-Airbnb-Market-Trends) · [Analyzing-Crime-in-Los-Angeles](https://github.com/wididestrianda01/Analyzing-Crime-in-Los-Angeles) · [Investigating-Netflix-Movies](https://github.com/wididestrianda01/Investigating-Netflix-Movies) · [Visualizing-the-History-of-Nobel-Prize-Winners](https://github.com/wididestrianda01/Visualizing-the-History-of-Nobel-Prize-Winners) · [Python-Data-Cleaning](https://github.com/wididestrianda01/Python-Data-Cleaning)

## Experience

**Project Engineer** (2021–2025)
Coordinated a USD 5.59M ERP upgrade with zero downtime; applied Six Sigma DMAIC to raise radio-system reliability from 72.15% to 99.46%.

**Estimator** (2018–2021)
Built a VBA Monte Carlo cost model that replaced commercial software; produced bid benchmarks used across the portfolio.

**Management Trainee** (2017–2018)
Built regression-based battery-lifetime models adopted as the facility's standard replacement-planning tool.

## Education

- **MSc Applied and Computational Mathematics (Financial Mathematics)** — KTH Royal Institute of Technology, 2025–2027 · GPA 4.06/5.00
- **MBA** — Institut Teknologi Bandung, 2020–2021 · GPA 4.00/4.00, Cum Laude
- **BSc Electrical Engineering** — Universitas Indonesia, 2012–2016 · GPA 3.67/4.00, Cum Laude

## Certifications

CFA Level I candidate (Aug 2026) · Project Management Professional (PMP) · PRINCE2 Practitioner · Six Sigma Green Belt · Qualified Risk Management Officer

## Languages

Indonesian (native) · English (full professional) · Swedish (beginner)

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-wididestrianda-blue)](https://www.linkedin.com/in/wididestrianda/)
[![GitHub](https://img.shields.io/badge/GitHub-wididestrianda01-181717)](https://github.com/wididestrianda01)
[![Tableau](https://img.shields.io/badge/Tableau-Public-orange)](https://public.tableau.com/app/profile/widi.destrianda)
