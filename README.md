# Construction Portfolio Analytics: Risk & Forecast Modeling

## 📊 Project Overview
Developed a comprehensive analytics pipeline to evaluate project health and schedule credibility across 1,300+ construction tasks. This project bridges the gap between manual Primavera P6 reporting and automated Machine Learning forecasting.

## 🛠️ Technical Achievements
- **Real-World Data Wrangling:** Ingested and cleaned an external construction dataset, mapping features such as labor requirements and equipment units to project outcomes.
- **Earned Value Management (EVM):** Engineered a performance quadrant dashboard using **SPI (Schedule Performance Index)** and **CPI (Cost Performance Index)** to isolate 100+ critical risks.
- **Predictive Analytics:** Deployed a Random Forest Regressor to forecast actual milestone completion.
- **Optimism Bias Quantification:** Identified a systemic underestimation in baselines, with the model achieving a **Mean Absolute Error (MAE) of 31.36 days** and recommending a **41-day schedule buffer** for new 30-day tasks to ensure fleet readiness.

## 📈 Business Impact (Babcock Context)
- **Schedule Credibility:** Provided a data-led "Correction Factor" for project baselines, preventing the common pitfall of over-promising on delivery dates.
- **Automated Risk Prioritisation:** Instantly categorised the portfolio into tiered risk levels (Critical, Alert, On-Target) to optimize resource allocation.

## 🐍 Tech Stack
- **Data:** Python (Pandas, NumPy), SQL Logic (DuckDB)
- **ML:** Scikit-Learn (Random Forest Regressor)
- **Visualisation:** Seaborn, Matplotlib