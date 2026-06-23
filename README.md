# Project overview
## Laptop price prediction comparison
model:
- Linear regression
- Random Forest regression
- XGBoost

## Original dataset
Features:
- company
- typename
- inches
- screenresolution
- cpu
- ram
- memory
- gpu
- opsys
- weight
- price

## Feature engineered
- CPU speed
- cpufamily
- gpufamily
- ppi
- x_res
- y_res

## Result

| Model             | MAE    | RMSE   | R²     |
| ----------------- | ------ | ------ | ------ |
| Linear Regression | 0.1770 | 0.2263 | 0.8555 |
| Random Forest     | 0.1551 | 0.2071 | 0.8790 |
| XGBoost           | 0.1348 | 0.1867 | 0.9016 |
