# EpiGuard AI

Research project on epidemic surveillance using public COVID-19 data from
Our World in Data. It studies:

1. **Forecasting** daily cases (7, 14, 28 days ahead) with uncertainty
   intervals, comparing simple baselines against ARIMA, Prophet, XGBoost
   and LSTM models.
2. **Anomaly detection** for outbreak spikes and reporting gaps.
3. **Privacy-preserving federated learning** that stays robust to faulty or
   malicious clients (planned).

## Status
Work in progress. Currently: data loading and exploration.

## Data
Our World in Data COVID-19 dataset (up to August 2024, CC BY 4.0):
https://catalog.ourworldindata.org/garden/covid/latest/compact/compact.csv

## Structure
- `data/` datasets (not tracked in Git)
- `notebooks/` exploration and experiments
- `src/` reusable code
- `reports/` figures and written report
