# 🏗️ Cheatsheet: Predictive Project Planning & EVM

## 1. The Core Variables
| Variable | Planning Term | What it represents |
| :--- | :--- | :--- |
| **`SPI`** | Schedule Index | Efficiency of time (Target > 1.0). Below 1.0 means you are behind schedule. |
| **`CPI`** | Cost Index | Efficiency of budget (Target > 1.0). Below 1.0 means you are over-budget. |
| **`MAE`** | Forecasting Error | Mean Absolute Error. Tells us how many days off our forecast is. |
| **`Baseline`** | P6 Target | The "Planned" state of the project before execution began. |

## 2. The Logic & The "Why"
*   **Quadrant Analysis:** We plot SPI vs. CPI. *Why?* To see if a project is "Trading Money for Time" (Ahead of schedule but over budget) or in a "Critical Failure" state (Behind schedule AND over budget).
*   **Random Forest Forecaster:** We use this model to predict the *Actual* duration. *Why?* Because humans are naturally optimistic when setting baselines. The AI looks at past failures to give a "Credible" completion date.

## 3. Interview Script (The Babcock Pitch)
> "In this project, I moved beyond standard manual reporting. I built a system that analyzes 500+ engineering tasks to calculate **SPI and CPI** performance. My **Random Forest model** then uses these metrics to provide a data-driven 'Correction' to the project baseline. This allows a Project Planner to report credible forecasts to stakeholders, ensuring that 'Fleet Readiness' is based on historical evidence rather than just estimates."