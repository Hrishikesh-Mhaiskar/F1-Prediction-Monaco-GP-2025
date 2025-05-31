# 🏎️ F1 Finish Position Prediction - Monaco GP (2025)

This project predicts the **finishing positions of drivers** in the **Formula 1 Monaco Grand Prix (2025)** using historical lap data, weather conditions, and machine learning models (Random Forest and XGBoost).

## Objective

Build an ML model that takes in:
- Lap times
- Weather conditions
- Historical race performance

...and predicts the **final standings of drivers** for the 2025 Monaco GP.

## Dataset

Data is fetched from the [FastF1](https://theoehrly.github.io/Fast-F1/) API for Monaco GPs from:
- **2022**
- **2023**
- **2024**

Each dataset includes:
- Lap-by-lap timing
- Driver metadata
- Weather (track temp, air temp, humidity, wind, pressure)

## 🛠️ Tech Stack

- Python
- [FastF1](https://pypi.org/project/fastf1/)
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib

## 📈 ML Models

Two models are trained:
- **Random Forest Regressor**
- **XGBoost Regressor**

## 📊 Features Used

- `Driver`, `Team`, `Track Temp`, `Air Temp`, `Humidity`, `Wind Speed`
- `LapTime`, `SpeedST`, `IsAccurate`
- Encoded features for driver & team names

## 🤝 Acknowledgements
- FastF1 for making F1 Data accessible.
