# MLflow Experiments: Wine Quality Prediction

This project uses the [UCI Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality) to build a regression model that predicts wine quality based on physicochemical tests. It uses **ElasticNet Regression**, logs experiments using **MLflow**, and integrates with **DagsHub** for remote tracking and model management.

---

## 🧪 What this project does

- Trains an ElasticNet regression model
- Evaluates performance using RMSE, MAE, and R²
- Logs metrics and parameters with MLflow
- Registers the trained model to DagsHub’s MLflow model registry

---

## 📦 Requirements

- Python 3.7+
- Packages listed in `requirements.txt`
- A [DagsHub](https://dagshub.com/) account with an API token

---

## 🔐 Environment Variables

Set your DagsHub credentials **in your terminal session** (do not hardcode or upload):

```bash
export MLFLOW_TRACKING_URI=https://dagshub.com/BadagiAnanya/Mlflow.mlflow
export MLFLOW_TRACKING_USERNAME=BadagiAnanya
export MLFLOW_TRACKING_PASSWORD=your_dagshub_api_token_here
