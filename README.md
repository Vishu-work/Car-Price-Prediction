# 🚗 Car Price Prediction using Machine Learning & Gradio

![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)  
![Machine Learning](https://img.shields.io/badge/Machine--Learning-Random%20Forest%20%7C%20Linear%20Regression-brightgreen)  
![Gradio](https://img.shields.io/badge/Gradio-UI-orange)  
![Status](https://img.shields.io/badge/Project-Completed-success)

> 🎯 **Predict the resale value of used cars based on real-world attributes like brand, fuel type, transmission, and more — with just a few clicks!**

---

## 🗂️ Table of Contents

- [📖 Project Overview](#-project-overview)  
- [📊 Dataset Description](#-dataset-description)  
- [⚙️ Features](#️-features)  
- [🧠 How It Works](#-how-it-works)  
- [🌐 Gradio Web Interface](#-gradio-web-interface)  
- [🚀 Getting Started](#-getting-started)  
- [🧪 Model Evaluation](#-model-evaluation)  
- [🔮 Future Improvements](#-future-improvements)  
- [🙌 Acknowledgements](#-acknowledgements)  
- [📬 Contact](#-contact)

---

## 📖 Project Overview

This project is a **car resale price prediction system** powered by **machine learning algorithms** and deployed through a sleek **Gradio web interface**.  
It allows users to enter details about a used car and receive a predicted resale price in real-time.

💡 Inspired by real data from **CarDekho**, this app is ideal for buyers, sellers, or enthusiasts trying to understand market prices.

---

## 📊 Dataset Description

📁 `CAR DETAILS FROM CAR DEKHO.csv`  
This dataset includes over 8,000 entries with key features:

| Feature         | Description                             |
|-----------------|-----------------------------------------|
| `name`          | Car model and brand                     |
| `year`          | Year of manufacture                     |
| `selling_price` | Price car was sold for (Target)         |
| `km_driven`     | Distance driven in kilometers           |
| `fuel`          | Fuel type: Petrol, Diesel, CNG, etc.    |
| `seller_type`   | Dealer / Individual / Trustmark Dealer  |
| `transmission`  | Manual or Automatic                     |
| `owner`         | Ownership history (First, Second, etc.) |

---

## ⚙️ Features

✅ Predict resale price of used cars  
✅ Clean and preprocess data (label encoding, one-hot encoding, outlier removal)  
✅ Trained using **Random Forest Regressor**  
✅ Saves the model pipeline using `joblib`  
✅ Fully interactive **Gradio UI** for quick predictions  
✅ Handles invalid inputs gracefully  
✅ Shareable public link to run the app instantly

---

## 🧠 How It Works

```mermaid
graph TD
A[Input via Gradio Form] --> B[Preprocessing Pipeline]
B --> C[Trained ML Model]
C --> D[Predicted Selling Price]
