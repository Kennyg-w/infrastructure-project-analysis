# 🏗️ Cheatsheet: Strategic Infrastructure Analytics

## 1. Professional Metrics
| Metric | Logic | Strategic Meaning |
| :--- | :--- | :--- |
| **SPI** | Planned / Actual Time | Efficiency of the schedule. Target is > 1.0. |
| **CPI** | Planned / Actual Cost | Efficiency of the budget. Target is > 1.0. |
| **MAE** | Prediction Error | **29.79 Days:** The margin of error for our "Realistic" forecast. |

## 2. The "Curve" vs "Cloud" (Pro Interview Answer)
*Question: "Why do your SPI and CPI points form a curve instead of a random cloud?"*
*Answer:* "In this specific simulation, I utilised a fixed random seed (42) for both duration and cost slippage to ensure **perfect reproducibility**. This created a mathematical dependency that reveals the 'Efficiency Frontier' of the project. In a raw real-world dataset, these would appear as a cloud, but the **Quadrant Logic** (Bottom-Left = Danger) remains the same."

## 3. Executive Pitch
> "I built a system that moves beyond 'status reporting' and into 'predictive risk management.' By mapping 1,300 tasks into a **Strategic Performance Quadrant**, I identified a systemic 60-day gap between planned and actual durations. This allows me to provide senior stakeholders with **evidence-based baselines**, protecting the critical path of heavy engineering projects."