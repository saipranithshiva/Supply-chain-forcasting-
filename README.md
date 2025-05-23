# Supply Chain Forecasting Project

This project showcases two forecasting techniques to estimate retail product demand using historical monthly data for three products.

## Objective
Improve forecast accuracy and reduce overstocking or stockouts through demand prediction models.

## Tools Used
- Excel
- Python
- Matplotlib

## Forecasting Techniques

### 1. Moving Average (3-month)
A basic method that averages the last 3 months of sales.

- Helps smooth short-term fluctuations.
- Used when demand is fairly stable.

**File:** `sales_data.xlsx`  
**Chart:** `forecast_chart.png`

---

### 2. Exponential Smoothing (Alpha = 0.5)
A more responsive method that gives higher weight to recent data.

- Better at adapting to trends or recent changes.
- Great for consistent demand environments.

**File:** `sales_data_exponential.xlsx`  
**Chart:** `forecast_chart_exponential.png`

---

## Next Steps
- Add regression forecasting and compare results.
- Automate forecasting using Python and integrate with real datasets.
