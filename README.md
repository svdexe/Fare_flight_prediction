# ✈️ Flight Price Predictor

## 📸 Demo

<div align="center">
  <img src="https://github.com/svdexe/Fare_flight_prediction/blob/main/Website%20output.png" alt="Flight Price Predictor Demo" width="800">
</div>

<div align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-blue.svg" alt="Python">
  <img src="https://img.shields.io/badge/Flask-Web%20App-green.svg" alt="Flask">
  <img src="https://img.shields.io/badge/ML-Random%20Forest-orange.svg" alt="ML">
</div>

<p align="center">
  <em>AI-powered flight price prediction using machine learning</em>
</p>



---

## 🎯 Overview

A machine learning web application that predicts flight prices using Random Forest algorithm. Built with Flask and deployed as an interactive web interface.

## ✨ Features

- **Random Forest ML Model** - 81% accuracy with hyperparameter tuning
- **Interactive Web App** - Clean UI with real-time predictions
- **Multiple Airlines** - IndiGo, Air India, Jet Airways, SpiceJet, etc.
- **Major Routes** - Covers all major Indian cities
- **Instant Results** - Real-time price estimation

## 🧠 Algorithm

**Random Forest Regressor**
- **Accuracy**: 81% R² Score
- **RMSE**: 2090.55
- **Features**: 29 engineered features
- **Training Data**: 10,000+ flight records

### Key Features
- **Temporal**: Journey date, departure/arrival times
- **Categorical**: Airlines, source/destination cities  
- **Flight Details**: Stops, duration (hours/minutes)
- **Preprocessing**: One-hot encoding, label encoding

## 📊 Performance

| Metric | Score |
|--------|-------|
| R² Score | 0.81 |
| RMSE | 2090.55 |
| MAE | 1297.42 |
| Training Accuracy | 95% |

## 🚀 Quick Start

```bash
git clone https://github.com/svdexe/Fare_flight_prediction.git
cd Fare_flight_prediction
pip install flask pandas numpy scikit-learn joblib
python app.py
```

Open `http://localhost:5000` in your browser.

## 🎮 Usage

1. Select departure/arrival dates
2. Choose source and destination
3. Pick airline and stops
4. Get instant price prediction

## 🔧 Tech Stack

- **Backend**: Python, Flask
- **ML**: Scikit-learn, Random Forest
- **Data**: Pandas, NumPy
- **Frontend**: HTML, CSS, JavaScript

## 👨‍💻 Author

**svdexe**
- GitHub: [@svdexe](https://github.com/svdexe)

---

<div align="center">
  <p>⭐ Star this repository if you found it helpful!</p>
</div>
