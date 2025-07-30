# Forecasting Grocery Sales Using Prophet

## Dataset
https://www.kaggle.com/competitions/store-sales-time-series-forecasting/overview

**Summary statistics of `y`:**
| Metric   | Value    |
|----------|----------|
| Count    | 1708     |
| Mean     | 2226.77  |
| Std Dev  | 783.62   |
| Min      | 0.00     |
| 25%      | 1873.50  |
| 50%      | 2285.00  |
| 75%      | 2652.00  |
| Max      | 9065.00  |
---

## Methodology

- Model: **Facebook Prophet**
- Features:
  - Daily seasonality
  - Yearly seasonality
  - Holiday effects
- Libraries used:
  - `prophet`, `pandas`, `matplotlib`, `scikit-learn` (for evaluation)
---

## Forecast Evaluation
Evaluation was done using standard regression metrics on the test dataset:
- **MAE (Mean Absolute Error):** 282.64
- **RMSE (Root Mean Square Error):** 482.91

The model shows good forecasting performance relative to the average sales (~2226), indicating that Prophet captured the general sales trends well.
---
