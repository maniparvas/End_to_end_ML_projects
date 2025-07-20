# 🔥 Fire Weather Index (FWI) Prediction Project

This project is a complete pipeline for predicting the **Fire Weather Index (FWI)** using machine learning. It includes everything from data analysis and model building to a Flask web interface for interactive predictions.

---

## 📌 Table of Contents
- [Project Overview](#project-overview)
- [Tech Stack](#tech-stack)
- [1. Exploratory Data Analysis (EDA)](#1-exploratory-data-analysis-eda)
- [2. Model Building](#2-model-building)
- [3. Web Application](#3-web-application)
- [How to Run the Project](#how-to-run-the-project)

---

## 🚀 Project Overview

This project aims to predict the **Fire Weather Index**, a key indicator of wildfire risk based on weather conditions like temperature, humidity, and wind. It includes:

- Data preprocessing and visualization
- Feature engineering
- Model training using machine learning
- A simple Flask web app to input conditions and predict FWI

---

## 🛠️ Tech Stack

- **Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Flask
- **Frontend**: HTML/CSS (with Bootstrap)
- **Environment**: Jupyter Notebook, VSCode, GitHub

---

## 📊 1. Exploratory Data Analysis (EDA)

We start by exploring the dataset:
- Checking for null values, outliers, and data types
- Visualizing correlations using heatmaps and scatter plots
- Understanding feature distributions and importance

Key insights:
- Temperature and wind speed are strong predictors of FWI
- Scaling and normalization improve model consistency

---

## 🤖 2. Model Building

### Steps:
1. **Train-Test Split**
2. **Feature Scaling**
3. **Model Training** using algorithms like Linear Regression or Random Forest
4. **Model Evaluation** using metrics like R², RMSE, MAE
5. **Model Saving** with `joblib` or `pickle`

Example:
```python
from sklearn.linear_model import LinearRegression
model = LinearRegression()
model.fit(X_train_scaled, y_train)
```

---

## 🌐 3. Web Application

A minimal Flask-based web application allows real-time prediction of FWI from user input.

### Features:
- Form input for weather data
- Backend processing and prediction
- Display of result on the same page

To run:
```bash
python app.py
```

App will run locally on `http://127.0.0.1:5000/`

---

## ▶️ How to Run the Project

1. **Clone the repository**
```bash
git clone https://github.com/your-username/fwi-prediction.git
cd fwi-prediction
```

2. **Create a virtual environment**
```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Run the web app**
```bash
python app.py
```


## 🙋‍♂️ Author

Built by [Maniparvas](https://github.com/maniparvas)  
Feel free to fork or contribute!

