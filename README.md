# 🚗 Car Price Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-1.51-FF4B4B?logo=streamlit)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![License](https://img.shields.io/badge/License-MIT-green)

A Machine Learning web application that predicts the resale price of used cars based on vehicle specifications such as age, mileage, engine capacity, fuel type, seller type, transmission, and more.

The application is built using **Python**, **Scikit-learn**, and **Streamlit**, with a trained **Random Forest Regressor** model.

---

## 📌 Project Overview

Buying or selling a used car often involves estimating its fair market value. This project uses historical car data to train a Machine Learning model capable of predicting the expected selling price of a vehicle.

The application provides an interactive web interface where users can enter vehicle details and receive an instant predicted price.

---

## 🚀 Features

- Predicts used car prices instantly
- User-friendly Streamlit interface
- Random Forest Regression model
- Feature scaling using Scikit-learn
- Clean and responsive UI
- Easy deployment using Streamlit Community Cloud

---

## 🛠️ Tech Stack

- Python
- Streamlit
- Scikit-learn
- Pandas
- NumPy
- Pickle
- Jupyter Notebook

---

## 📂 Project Structure

```
CarPricePrediction/
│
├── app/
│   └── car_price_predictor_app.py
│
├── data/
│
├── saved_models/
│   └── RandomForestRegressor.pkl
│
├── saved_scaling/
│   └── scaler.pkl
│
├── main.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/bhoomiiiiis/CarPricePrediction.git

cd CarPricePrediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the Streamlit application

```bash
streamlit run app/car_price_predictor_app.py
```

---

## 📊 Model Information

| Model | Random Forest Regressor |
|--------|-------------------------|
| Problem Type | Regression |
| Framework | Scikit-learn |
| Scaling | StandardScaler |
| Output | Predicted Car Price |

---

## 🎯 Input Features

The model uses the following features:

- Vehicle Age
- Kilometers Driven
- Mileage
- Engine Capacity
- Maximum Power
- Number of Seats
- Seller Type
- Fuel Type
- Transmission Type

---

## 💻 Application Preview

### Home Page

> Add a screenshot here after running the application.

```
images/home_page.png
```

### Prediction Result

> Add another screenshot showing the prediction.

```
images/prediction_result.png
```

---

## 📈 Future Improvements

- Add car brand encoding
- Predict confidence interval
- Deploy using Docker
- Store prediction history
- Connect with MySQL database
- Improve UI with charts and analytics

---

## 🌐 Deployment

The application can be deployed on:

- Streamlit Community Cloud
- Render
- Railway
- Hugging Face Spaces

---

## 👨‍💻 Author

Bhumika Sain

GitHub: https://github.com/bhoomiiiiis

LinkedIn: https://linkedin.com/in/bhumika-sain-b22b63209

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.
