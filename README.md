# UrbanCart Milestone 1 — Next-Month Spend

Regression project for UrbanCart finance: predict `NextMonthSpend` from customer tenure, average order value, recent orders, and region.

## What's in this repo

- `Assignment2.ipynb` — full walkthrough: data check, outliers, train/test split, Linear Regression vs Random Forest, test metrics, and recommendation.
- `milestone-1-customer-spend.csv` — ~20,000 customers used to train and test the models.

## Results (held-out test set)

| Model | MAE | RMSE | R² |
|---|---|---|---|
| Linear Regression | 9.85 | 12.33 | 0.83 |
| Random Forest | 10.56 | 13.17 | 0.806 |

**Recommendation:** use Linear Regression. It was more accurate here and easier to explain.

## How to run

1. The CSV is in this repo. Update the notebook `read_csv` path to `milestone-1-customer-spend.csv` if it still points to your Downloads folder.
2. Open `Assignment2.ipynb` in Jupyter and run all cells.
