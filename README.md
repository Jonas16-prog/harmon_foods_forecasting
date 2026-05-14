# Harmon Foods Sales Forecasting

## Overview

This project analyzes monthly cereal shipment data from **Harmon Foods, Inc.** in order to understand sales behavior and build predictive models for future shipments.

The study focuses on:

- long-term shipment trends,
- seasonality effects,
- promotional campaign impacts,
- lagged demand behavior,
- and forecasting monthly shipments for 1988.

The project is based on the *Harmon Foods* business case study and applies quantitative methods commonly used in business analytics and demand forecasting.

---

## Business Context

Harmon Foods faced major challenges in predicting cereal shipments accurately. Poor forecasts created operational problems in:

- production planning,
- inventory management,
- advertising allocation,
- budgeting,
- and profit planning.

The objective of this analysis is to develop a forecasting approach capable of improving shipment predictions while taking into account:

- seasonality,
- consumer promotions,
- dealer allowances,
- and delayed promotional effects.

---

## Objectives

- Analyze shipment trends over time
- Identify seasonal patterns
- Study the effect of promotions on demand
- Build regression-based forecasting models
- Evaluate correlations between explanatory variables
- Forecast monthly shipments for 1988
- Generate managerial recommendations

---

## Methods Used

### Time Series Analysis

- Trend visualization
- Moving averages (MA12)
- Seasonal analysis
- Deseasonalization

### Statistical & Predictive Modeling

- Multiple Linear Regression
- Correlation Analysis
- Lag Variables
- Forecasting Techniques

### Data Visualization

- Shipment evolution plots
- Trend curves
- Forecast comparison tables

---

## Technologies & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Project Structure

```text
harmon_foods_forecasting/
│
├── data/
│   └── Harmon_Foods_data.csv
│
├── notebooks/
│   └── analyse.ipynb
│
├── results/
│   ├── tendance.png
│   ├── Harmon_1988_forecast.csv
│   └── Harmon_1988_forecast_table.csv
│
├── docs/
│   ├── project_statement.pdf
│   └── final_report.pdf
│
├── requirements.txt
└── README.md
```


This project analyzes monthly cereal shipments from Harmon Foods and builds forecasting models to predict future shipments.

## Objectives

- Analyze monthly shipment trends
- Identify seasonality effects
- Study the impact of promotional activities
- Build regression-based forecasting models
- Forecast shipments for 1988

## Methods Used

- Time series analysis
- Moving average trend analysis
- Seasonality analysis
- Lag variables
- Multiple linear regression
- Forecast evaluation

## Project Structure

```text
harmon-foods-forecasting/
├── data/
├── notebooks/
├── results/
└── README.md
```

## Trend Visualization

![Trend](results/tendance.png)
