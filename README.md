# 🏎️ F1 Podium Prediction: 2025 Miami Grand Prix

This project predicts the **top 3 finishers** (podium positions) for the 2025 Formula 1 Miami Grand Prix using machine learning. It combines historical race data, qualifying times, live weather forecasts, and team performance metrics to estimate race pace and determine podium outcomes.

---

## 📌 Project Description

The goal of this project is to use a data-driven approach to forecast Formula 1 race results. By analyzing data from the 2024 Miami GP and combining it with 2025 qualifying results and real-time weather information, we train a regression model to estimate each driver’s adjusted race pace. The drivers with the lowest predicted pace are selected as the expected podium finishers.

This end-to-end pipeline includes:

- 🔎 **Data extraction** from FastF1 (lap, sector, pit stop data)
- 🌦️ **Weather integration** via OpenWeatherMap API
- 🛠️ **Feature engineering** (sector averages, pit strategy, team strength)
- 🧠 **Machine learning modeling** using `GradientBoostingRegressor`
- 📊 **Race pace prediction** and podium classification
- 🖼️ **Visualizations** to compare actual vs. predicted performance and feature importance

The final output ranks all drivers by predicted race pace and highlights the top 3 finishers.

---

## 🚀 Key Technologies

- Python, Pandas, NumPy
- FastF1 for race session data
- OpenWeatherMap API for forecasts
- Scikit-learn for machine learning
- Matplotlib for data visualization

---

## ✅ Outcome

- Achieved high model accuracy (MAE ~0.23s, R² ~0.91)
- Successfully predicted McLaren and Red Bull as top contenders
- Produced a reusable pipeline for future F1 race prediction tasks

---

