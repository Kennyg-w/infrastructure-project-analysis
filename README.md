# Predictive Project Analytics: Naval & Construction Portfolio

## 📊 Project Overview
Developed an end-to-end analytics pipeline for managing a portfolio of 500+ complex engineering tasks. This project integrates standard Project Planning (Primavera P6 logic) with Machine Learning to predict milestone completion and identify critical path risks.

## 🛠️ Technical Achievements
- **Big Data Wrangling:** Ingested and cleaned a real-world construction dataset, automating the calculation of project durations and cost variances.
- **Earned Value Management (EVM):** Engineered a dashboard using **SPI (Schedule Performance Index)** and **CPI (Cost Performance Index)** to visualise portfolio health at scale.
- **Automated Risk Logic:** Built a categorisation model to isolate "Critical" tasks—identifying that a significant portion of the portfolio required immediate resource intervention.
- **Predictive Analytics:** Deployed a **Random Forest Regressor** to forecast actual task durations, achieving a Mean Absolute Error (MAE) of 0.96 days, significantly improving schedule credibility.

## 📈 Business Impact (Babcock Context)
- **Reduced Risk Latency:** Automated detection of schedule slippage, allowing for intervention weeks before a milestone is missed.
- **Data-Led Decisions:** Provided a quantitative basis for adjusting project baselines based on historical performance.

## 🐍 Tech Stack
- **Data:** Python (Pandas, NumPy), SQL Logic (DuckDB)
- **ML:** Scikit-Learn (Random Forest)
- **Visualisation:** Seaborn, Matplotlib