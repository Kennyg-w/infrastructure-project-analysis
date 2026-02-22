# 1. Infrastructure & Heavy Engineering Analytics: Predictive Risk & Baseline Forecasting

## 📊 Project Overview
Developed a strategic health dashboard to monitor a portfolio of 1,300+ heavy infrastructure tasks. This project integrates Earned Value Management (EVM) with Machine Learning to identify systemic optimism bias and provide data-led schedule corrections.

## 🛠️ Technical Achievements
- **Strategic Performance Quadrant:** Engineered a visualisation mapping SPI vs. CPI to isolate systemic risks across 1,300 records.
- **Risk Distribution Modeling:** Programmatically categorised the portfolio into tiered risk levels (Critical, Alert, On-Target) to optimise resource allocation.
- **Predictive Analytics:** Deployed a Random Forest Regressor to forecast actual task durations with a **Mean Absolute Error (MAE) of 29.79 days**.
- **Optimism Bias Quantification:** Identified a systemic 60.1-day underestimation in 30-day task baselines, providing a data-driven "Correction Factor" to ensure project credibility.

## 📈 Business Impact
- **Reduced Risk Latency:** Automated detection of schedule slippage, allowing for intervention weeks before milestones are reached.
- **Improved Forecasting:** Provided a quantitative basis for adjusting project baselines based on historical performance friction.

## 🐍 Tech Stack
- Python (Pandas, NumPy, Scikit-Learn), SQL Logic (DuckDB), Seaborn, Matplotlib.