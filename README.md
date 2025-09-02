# MLflow Hyperparameter Tuning Experiments

This repository demonstrates the use of **MLflow** for experiment tracking and **hyperparameter tuning** with different techniques:
- Grid Search
- Random Search (via scikit-learn)
- Bayesian Search using **Hyperopt**

The experiments are run locally in **VS Code** with MLflow Tracking Server, and the sample dataset used is the **Titanic dataset**.

---

## Repository Contents

- `MLFlow_practical.ipynb` – Basic MLflow logging example (parameters, metrics, model).
- `MLFlow_Grid_search.ipynb` – Hyperparameter tuning with Grid Search tracked in MLflow.
- `MLFlow_Hyperopt_search.ipynb` – Hyperparameter tuning with Hyperopt (Bayesian optimization).
- `Hyperopt.ipynb` – Standalone Hyperopt tuning example.
- `titanic.csv` – Sample dataset used for training/testing.
- `requirements.txt` – Python dependencies for running the experiments.

---

## Create a virtual environment

python -m venv .venv
.venv\Scripts\activate      # Windows

## Install dependencies
pip install -r requirements.txt

## Run MLflow tracking server locally
mlflow server --host 127.0.0.1 --port 8000




