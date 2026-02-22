# ⚓  Infrastructure & Heavy Engineering Analytics  Predictive Risk & Baseline Forecasting

## 📊 Project Overview
Developed an end-to-end analytics pipeline to monitor 1,300+ heavy infrastructure tasks. This project integrates Earned Value Management (EVM) with Machine Learning to identify systemic optimism bias and provide data-led schedule corrections.

## 🛠️ Technical Achievements
- **Big Data Engineering:** Cleaned and processed 1,300+ records, mapping labor and material constraints to project outcomes.
- **EVM Implementation:** Engineered a performance quadrant dashboard using **SPI** and **CPI** metrics to isolate 200+ "Critical" schedule risks.
- **Predictive Analytics:** Deployed a Random Forest Regressor to forecast actual task durations with a **Mean Absolute Error (MAE) of 29.79 days**.
- **Optimism Bias Quantification:** Identified a systemic 60.1-day underestimation in 30-day task baselines, providing a data-driven "Correction Factor" to ensure fleet readiness.

## 📈 Business Impact
- **Schedule Credibility:** Provided a quantitative basis for adjusting project baselines, preventing the common pitfall of over-promising on delivery dates.
- **Automated Risk Logic:** Programmatically flagged the top 5 "Project Killer" tasks threatening the critical path.

## 🐍 Tech Stack
- **Data:** Python (Pandas, NumPy), SQL Logic (DuckDB)
- **ML:** Scikit-Learn (Random Forest Regressor)
- **Visualisation:** Seaborn, Matplotlib