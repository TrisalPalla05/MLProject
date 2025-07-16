# 🏎️ ML Project: Predicting Top 3 Race Finishers Using Ensemble Learning

This machine learning project predicts whether a Formula 1 driver finishes in the **Top 3** using ensemble learning techniques. The model combines multiple algorithms to improve prediction accuracy and robustness.

## 📌 Problem Statement

Predict if a given driver will finish in the top 3 positions in a race using historical data of drivers, races, constructors, and results.

---

## 🧠 ML Techniques Used

- 🧹 Data Preprocessing
- 🧩 Feature Engineering
- 🤖 Ensemble Modeling (Random Forest, XGBoost, Voting Classifier)
- ✅ Model Evaluation (Confusion Matrix, Accuracy, F1 Score)

---

## 📁 Dataset Sources

Datasets include:

- `drivers.csv`
- `constructors.csv`
- `races.csv`
- `results.csv`
- `status.csv`

These files include metadata on race results, driver info, team constructors, and finish statuses.

---

## 📊 Features Used

Examples of engineered and raw features:

- Driver ID & Constructor ID
- Grid Position
- Number of pit stops
- Race year & round
- Track conditions (if available)
- Race status (finished, retired, etc.)

---

## 🔍 Target Variable

- Binary output:
  - `1`: Driver finished in Top 3
  - `0`: Otherwise

---

## 🚀 Models Implemented

- Random Forest Classifier
- XGBoost Classifier
- Voting Classifier (Ensemble of RF + XGB + others)

---

## 📈 Results

- Accuracy: ~**99%**
- Confusion Matrix: Visualized in the notebook



---
