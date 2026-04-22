# An Empirical Analysis of Volatility in Cotton Futures

## Overview
This project provides an empirical analysis of volatility dynamics and tail risk in cotton futures markets using econometric models.

The study uses daily data for the continuous cotton futures contract (CT=F) from 2000 to 2026 and investigates key stylized facts such as:
- Volatility clustering  
- Heavy-tailed distributions  
- Asymmetric responses to shocks  

---

## Methodology

The analysis is based on:

- **GARCH(1,1)** as a benchmark model  
- **GJR-GARCH(1,1)** to capture asymmetric volatility  
- **Student-t distribution** to model fat tails  
- **ARMA models** for mean dynamics  

Risk is evaluated using:

- **Value at Risk (VaR)**  
- **Expected Shortfall (ES)**  

---

## Key Features

- Volatility modeling with GARCH-type models  
- Tail risk estimation and backtesting  
- Regime classification (low, medium, high volatility)  
- Identification of stress periods (e.g. 2008, 2011, 2022)  
- Empirical analysis of risk dynamics in commodity markets  

---

## Results

The analysis shows that:

- Cotton futures exhibit strong **volatility persistence**  
- Returns are **non-normal** with heavy tails  
- Volatility reacts **asymmetrically** to shocks  
- Risk is **state-dependent** and increases significantly during stress regimes  

---

## Requirements

Install required R packages:

```r
install.packages(c(
  "quantmod",
  "tidyverse",
  "rugarch",
  "MSwM",
  "PerformanceAnalytics",
  "tseries",
  "ggplot2",
  "lubridate"
))
```
---
## Disclaimer
This project is for research and educational purposes only and does not constitute financial advice.
