# Car-Price-Prediction
🚗 Car Price Prediction Using Machine Learning & Gradio

This project is a car price prediction system built with machine learning techniques trained on a dataset from CarDekho. It includes feature preprocessing, model training, and an interactive Gradio-based web interface for real-time predictions.

📊 Dataset

The dataset used is:

📁 CAR DETAILS FROM CAR DEKHO.csv

It contains various car attributes including:

name (car model)

year (manufacturing year)

selling_price (target variable)

km_driven

fuel (Petrol, Diesel, etc.)

seller_type, transmission, owner, etc.

⚙️ Features

✅ Predicts resale price of a used car

✅ Preprocessing of categorical and numerical data

✅ Trained with regression models (e.g. Linear Regression, Random Forest)

✅ Saves trained model using joblib

✅ Deployed using Gradio for a simple, shareable interface

✅ Handles invalid input with built-in exception handling

🧠 How It Works

Data Cleaning: Handle missing values, convert categories using Label Encoding or One-Hot Encoding.

Model Training: Trained with regression algorithm (default: RandomForestRegressor).

Model Persistence: Save the model and preprocessing pipeline using joblib.

Gradio App: An interactive UI accepts user input and predicts price in real time.

🌐 Gradio App

Input fields:

Car Name

Year

Kilometers Driven

Fuel Type

Seller Type

Transmission

Owner Type

Output:
Predicted Selling Price in ₹ (INR)


