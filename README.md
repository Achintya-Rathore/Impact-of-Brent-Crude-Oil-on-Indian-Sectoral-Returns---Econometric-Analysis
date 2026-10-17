# Impact of Brent Crude Oil Prices on Indian Equity Sectors

### An Econometric Analysis Using Python

## 📌 Project Overview

This project investigates the relationship between global Brent crude oil price movements and six major Indian equity sectoral indices using econometric time-series analysis.

Using **96 monthly observations spanning 8 years**, the study examines whether movements in international crude oil prices influence Indian sectoral equity returns, and whether any predictive relationships exist between oil price changes and sectoral market performance.

The complete analytical pipeline was developed in Python, combining statistical analysis, time-series econometrics, and multivariate modelling to evaluate the transmission of global oil price movements into Indian equity markets.

## 🎯 Research Objectives

- Examine the correlation between Brent crude oil returns and Indian sectoral equity returns.
- Test the stationarity of financial time series using the Augmented Dickey-Fuller (ADF) test.
- Investigate predictive relationships using Granger causality tests.
- Develop a Vector Autoregression (VAR) model with information criteria-based lag selection.
- Analyse the dynamic response of sectoral equity returns to oil price shocks using Impulse Response Functions (IRFs).
- Assess whether global crude oil movements have a statistically significant relationship with Indian sectoral equity markets.

## 📊 Sectors Analysed

The study covers six Indian equity sectoral indices:

| Sector | Index |
|---|---|
| Automobile | Nifty Auto |
| Information Technology | Nifty IT |
| Fast-Moving Consumer Goods | Nifty FMCG |
| Pharmaceuticals | Nifty Pharma |
| Oil and Gas | Nifty Oil & Gas |
| Real Estate | Nifty Realty |

Brent crude oil serves as the global commodity variable against which sectoral equity market movements are evaluated.

## 🛠️ Methodology

The research follows a structured econometric workflow:

1. **Descriptive Statistics and Normality Testing** — Summarised return distributions and examined their statistical properties.
2. **Pearson Correlation Analysis** — Evaluated linear relationships between crude oil and sectoral equity returns, including p-value matrices.
3. **Augmented Dickey-Fuller (ADF) Test** — Tested time-series stationarity.
4. **Granger Causality Testing** — Tested predictive relationships across four lag periods.
5. **Vector Autoregression (VAR)** — Modelled dynamic interactions between the variables, selecting lags using information criteria.
6. **Impulse Response Function (IRF)** — Examined the dynamic response of sectoral equity returns to shocks over a 10-month horizon.

## 🔍 Key Findings

The results indicate **limited evidence of short-term predictive transmission from Brent crude oil movements to Indian sectoral equity markets**.

- **Oil & Gas:** A statistically significant Granger-causal relationship was identified at Lag 1, with an F-statistic of 4.50 and a p-value of 0.037.
- **Automobile:** No statistically significant Granger-causal relationship was identified.
- **Information Technology:** No statistically significant Granger-causal relationship was identified.
- **FMCG:** No statistically significant Granger-causal relationship was identified.
- **Pharmaceuticals:** No statistically significant Granger-causal relationship was identified.
- **Realty:** No statistically significant Granger-causal relationship was identified.

At the 5% significance level, the Oil & Gas result provides evidence of a short-term predictive relationship in the tested specification. The findings for the other sectors do not provide sufficient evidence of Granger causality under the tested lag structure.

### Interpretation

The findings suggest that the relationship between global crude oil movements and Indian sectoral equity returns may be sector-specific rather than uniform across the market. The Oil & Gas sector exhibits the clearest short-term predictive relationship in this analysis.

These findings do not establish structural causation or prove that domestic factors dominate all other influences. They should be interpreted in the context of the sample period, model specification, and statistical limitations.

## 💻 Technology Stack

- **Python** — Core programming language
- **Pandas** — Data manipulation and analysis
- **NumPy** — Numerical computation
- **SciPy** — Statistical analysis
- **Statsmodels** — Econometric testing and VAR modelling
- **Matplotlib / Seaborn** — Data visualisation
- **Jupyter Notebook** — Research workflow and documentation

## 📁 Project Workflow

The analysis follows this sequence:

**Data Preparation → Return Calculation → Descriptive Statistics → Correlation Analysis → Stationarity Testing → Granger Causality → VAR Modelling → Impulse Response Analysis → Interpretation**

## 📈 Skills Demonstrated

- Financial time-series analysis
- Econometric modelling
- Statistical hypothesis testing
- Time-series stationarity analysis
- Granger causality testing
- Vector Autoregression (VAR)
- Impulse Response Function analysis
- Python-based financial research
- Interpretation of empirical financial results

## ⚠️ Limitations

- The analysis uses 96 monthly observations, which limits the statistical power of more complex models.
- Granger causality indicates predictive relationships, not necessarily true economic causation.
- Results may depend on the sample period, return transformations, lag selection, and model specification.
- A statistically insignificant result does not establish that no relationship exists.
- The analysis does not establish that domestic market conditions are the primary drivers of Indian equities without directly modelling domestic explanatory variables.


## 👤 Author

**Achintya Rathore**

BBA Student | Finance and Econometric Research | Python for Finance

---

*This project was conducted for academic and research purposes. It is not investment advice and should not be interpreted as a trading strategy.*
