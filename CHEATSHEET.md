# 🏗️ Cheatsheet: Predictive Project Planning & ML

## 1. Final Model Metrics
| Metric | Value | Interpretation |
| :--- | :--- | :--- |
| **MAE** | **29.79 Days** | The average margin of error for milestone completion forecasts. |
| **Baseline** | **30.0 Days** | The original "Optimistic" estimate. |
| **Forecast** | **90.1 Days** | The model's "Realistic" predicted duration based on historical friction. |
| **Correction**| **+60.1 Days** | The necessary buffer recommended to protect the critical path. |

## 2. Technical Terms for Interviews
*   **Stochastic Slippage:** The random delays modeled between 0.9x and 1.6x of the baseline to simulate real-world engineering friction.
*   **Random State (42):** The seed used to ensure **Reproducibility**, allowing the results to remain consistent across different model runs.
*   **EVM Quadrants:** The visualization of Schedule (SPI) vs. Cost (CPI) used to identify underperforming project sectors.

## 3. The "Babcock" Pitch
> "I built a model that identifies **Systemic Optimism Bias**. While the original plan for this portfolio suggested 30-day turnarounds, my analysis proved a 90-day cycle was more realistic. By applying a 60-day correction factor, I can ensure that resource planning for naval refits is based on data-driven evidence rather than best-case scenarios."