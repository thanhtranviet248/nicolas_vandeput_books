# Nicolas Vandeput Books — Notes, Summaries & Code

Personal study repository for the supply chain books by **Nicolas Vandeput**. For each book it collects the book file, my own summary and review, and (where relevant) Python notebooks that re-implement the models from the book.

## Repository structure

```
.
├── data_science_for_supply_chain_forecasting/
│   ├── data_science_for_supply_chain_forecasting.pdf
│   ├── summary_and_review_data_science_for_supply_chain_forecasting.pdf
│   ├── part_1_statistical_forecast.ipynb
│   └── part_2_machine_learning_forecast.ipynb
└── demand_forecasting_best_practices/
    ├── demand_forecasting_best_practices.pdf
    └── summary_and_review_demand_forecasting_best_practices.pdf
```

## Books

### 1. Data Science for Supply Chain Forecasting

| File | Description |
|------|-------------|
| `data_science_for_supply_chain_forecasting.pdf` | The book |
| `summary_and_review_data_science_for_supply_chain_forecasting.pdf` | Summary and review |
| `part_1_statistical_forecast.ipynb` | Part 1 – statistical forecasting models |
| `part_2_machine_learning_forecast.ipynb` | Part 2 – machine learning forecasting models |

**Part 1 – Statistical forecast** covers:
- Data preparation and forecasting KPIs (bias, MAE, RMSE, …)
- Moving average
- Simple, double and triple (additive / multiplicative) exponential smoothing, with damped trend
- Model parameter optimization
- Outlier detection and handling

**Part 2 – Machine learning forecast** covers:
- Turning time series into a supervised learning dataset; train/test split
- Linear regression, decision tree, random forest, extra trees
- AdaBoost and XGBoost (including `MultiOutputRegressor` and early stopping)
- Hyperparameter and feature optimization, feature importance
- Demand drivers, leading indicators and categorical features

### 2. Demand Forecasting Best Practices

| File | Description |
|------|-------------|
| `demand_forecasting_best_practices.pdf` | The book |
| `summary_and_review_demand_forecasting_best_practices.pdf` | Summary and review |

### Coming soon

- **Inventory Optimization: Models and Simulations**

## Running the notebooks

The notebooks use Python with the usual data-science stack:

```bash
pip install numpy pandas matplotlib scikit-learn xgboost jupyter
jupyter notebook
```

Then open the notebooks in `data_science_for_supply_chain_forecasting/`.

## Disclaimer

The books are the work of Nicolas Vandeput and belong to their respective copyright holders. Summaries, reviews and code in this repository are personal study material.
