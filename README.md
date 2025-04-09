# Take-Home Exercise 3

This project applies a Random Forest Regression model to predict Formula 1 lap times using historical race data. The experiment was tracked and logged using MLflow.

## Model

- **Model Type:** Random Forest Regressor
- **Input Features:** `driverId`, `lap`, `position`
- **Target Variable:** `milliseconds`

## Experiment Tracking

- **Tool:** MLflow
- **Parameters logged:** n_estimators, max_depth, random_state
- **Metrics logged:** MSE, MAE, R²
- **Artifact logged:** Prediction plot (`img/prediction_plot.png`)
- **Best Run Example:** `persistent-skunk-413`

## Screenshots

All screenshots are saved in the `/img` folder:
- `mlflow_homepage.png`: MLflow experiment UI showing multiple runs
- `best_run_details.png`: Detailed view of the best-performing run

Submitted by: Yu Chen, UNI: yc4566

