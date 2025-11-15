# 🚕 Cab Fare Prediction Based on Time Series & Machine Learning

*A Research-Driven Predictive Analytics Project*

## 📌 Overview

This project implements **cab fare prediction** using **time-series analysis** and **machine learning techniques**, inspired by our research paper published in **IJIRT, Volume 10, Issue 2 (2023)**.

The goal is to **predict taxi fares before booking**, enabling transparency for customers and helping companies avoid unfair pricing practices.

The system uses historical data, dynamic real-time factors, and multiple ML models to accurately estimate fare amounts.
<img width="1600" height="1029" alt="image" src="https://github.com/user-attachments/assets/dd8f3b35-9565-4e04-8508-c4c75302e7a4" />

---

## ⭐ Key Features

* 📅 **Time-Series Based Forecasting**
* 🌦️ Incorporates contextual factors such as:
  
  * Weather
  * Cab availability
  * Cab size
  * Distance between locations
* 🤖 Machine Learning Models

  * Linear Regression
  * Random Forest
  * KNN
  * Gradient Boosting
  * Lasso Regression
* 🧪 Model training, evaluation & feature engineering
* 📊 Trend, seasonality, residual decomposition
* 🔍 Supports fare prediction within 40 km range

---

## 🧠 Motivation

The taxi industry is rapidly growing, but fare inconsistencies across service providers often lead to **overcharging**. Predictive analytics allows us to build a transparent and fair fare estimation system using historical ride patterns and dynamic features.

Our research demonstrates how various ML techniques can accurately forecast cab fares, helping both users and service providers make informed decisions.

---

## 📚 Literature References

This work is based on extensive research from:

* Deep learning frameworks for fare prediction
* Time series methods like ARIMA
* Classical ML models such as Random Forest and Ensemble Models
* Forecasting using ANN and hybrid ML approaches

(Full list included in the research paper)

---

## 🏗️ System Architecture

The system consists of the following stages:

### 1️⃣ Data Collection

* NYC taxi datasets / custom datasets
* Time-series data extraction

### 2️⃣ Preprocessing

* Cleaning missing values
* Outlier removal
* Feature transformation
* Time feature extraction (year, month, date, day, hour)

### 3️⃣ Feature Engineering

Key features used for prediction include:

* Passenger Count
* Year / Month / Date
* Day of the week
* Hour of the trip
* Trip Distance

### 4️⃣ Model Training

Models trained & compared:

* Linear Regression
* Lasso Regression
* Random Forest Regressor
* KNN
* Gradient Boosting
* Regression Trees

### 5️⃣ Evaluation

Metrics used:

* RMSE
* MAE
* MSE
* Error Rate (Industry Standard < 5%)

Our study found:

> **Multiple Regression & Lasso performed more consistently than Regression Tree models.**

---

## 🖥️ Technology Stack

### 🔧 Software Requirements

* Python 3.x
* Anaconda Navigator
* Jupyter Notebook

### 💻 Hardware Requirements

* Windows 10 / 11
* Minimum 4 GB RAM

---

## 📂 Project Structure

```
Cab-Fare-Prediction/
│── data/               # Dataset files
│── notebooks/          # Jupyter notebooks
│── src/                # Feature engineering & ML scripts
│── models/             # Trained models
│── README.md
│── requirements.txt
```

---

## 📈 Results

The final model successfully predicts fares using the seven key features:

| Feature         | Description             |
| --------------- | ----------------------- |
| Passenger Count | No. of passengers       |
| Year            | Trip year               |
| Month           | Trip month              |
| Date            | Day of month            |
| Day             | Weekday                 |
| Hour            | Time of the day         |
| Distance        | Trip distance (≤ 40 km) |

The model produced **accurate fare estimates** with **low error rates**, meeting the research requirements.

---

## 🔮 Future Scope

The system can be enhanced by adding:

* 🚀 A full **web UI using Django or Streamlit**
* 📍 Real-time GPS integration
* ☁️ Cloud deployment (AWS/GCP)
* 🧭 Optimization models for surge pricing detection
* 📱 Mobile app for instant fare prediction

---

## 👩‍💻 Authors

**Ayesha Siddiq**
**Shamamah Firdous**
Students, BE [AI & DS], CS & AI Dept,
MJCET, OU Hyderabad, TS, India

📧 Contact:

* Shamamah Firdous-[firdous.s@northeastern.edu]
