# 🏗️ Cheatsheet: Real-World Project Planning & ML

## 1. Professional Metrics & Results
| Metric | Result | Interpretation |
| :--- | :--- | :--- |
| **MAE** | **31.36 Days** | On average, our completion forecast is within one month of reality in a highly volatile environment. |
| **Correction** | **+41.0 Days** | For a typical 30-day task, the model suggests a 71-day duration is more realistic based on historical performance. |
| **Status** | **Critical Delay** | Any task with an SPI < 0.8 is flagged for immediate executive review. |

## 2. The Logic: "Optimism Bias"
*   **The Problem:** Humans set baselines based on "best-case scenarios."
*   **The ML Solution:** The Random Forest model looks at "historical friction" (labor/equipment constraints). It found that for this dataset, tasks are consistently under-estimated by over 100%. 
*   **The Result:** By recommending an adjustment of **41 days**, we protect the "Critical Path" from unexpected slippage.

## 3. Interview Script (The Babcock Pitch)
> "In my analysis of 1,300 engineering tasks, I moved beyond standard tracking to identify **Systemic Optimism Bias**. While the original baselines suggested 30-day turnarounds, my predictive model — which achieved a Mean Absolute Error of 31 days—revealed that a 71-day cycle was historically more accurate. For a Project Planner at Faslane, this means I can provide stakeholders with **credible, evidence-based forecasts** rather than aspirational dates, directly supporting mission-readiness."