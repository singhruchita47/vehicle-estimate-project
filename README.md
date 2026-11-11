# 🚗 Vehicle Price Prediction System Using Machine Learning

An end-to-end Machine Learning project designed to predict used car resale prices based on key vehicle features such as present ex-showroom price, vehicle age, kilometers driven, fuel type, transmission type, and seller details. 

This repository contains data preprocessing workflows, regression model evaluation scripts, data visualization graphs, and an interactive Gradio web application for real-time predictions.

---

## 📌 Project Overview

Determining a fair market price for pre-owned cars is often challenging due to subjective appraisal and market inconsistencies. This project addresses the issue by leveraging supervised Machine Learning algorithms trained on historical car sales data to provide instant, data-backed price estimations.

* **Developed by:** Team 3 (Sneha Meena, Aparna Khawade, Ruchita Singh, Dolly Deshmukh, Akanksha Meena, Shrushti Rajuke)
* **Institution:** Scope Global Skills University (SGSU), Bhopal, MP
* **Course:** B.Tech CSE (Artificial Intelligence & Data Science)
* **Dataset:** [CarDekho Vehicle Dataset (Kaggle)](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho)

---

## 🛠️ Features & Highlights

- **Data Cleaning & Engineering:** Derived key analytical attributes like `Vehicle Age` and transformed categorical variables into machine-readable numeric formats.
- **Model Training & Comparison:** Evaluated multiple supervised regression algorithms (Linear Regression, Decision Tree, Random Forest, and Gradient Boosting).
- **High Performance:** Achieved top accuracy with Ensemble Learning models (Gradient Boosting / Random Forest $R^2 \approx 0.94 - 0.95$).
- **Interactive Web UI:** Integrated an easy-to-use dynamic interface built with Gradio for real-time inference.

---

## 📊 Dataset Parameters

| Feature Name | Type | Description |
| :--- | :--- | :--- |
| `Car_Name` | Categorical | Brand and model name of the vehicle |
| `Year` | Numerical | Original purchase year |
| `Selling_Price` | Numerical (Target) | Resale price in Lakhs (₹) |
| `Present_Price` | Numerical | Current ex-showroom price in Lakhs (₹) |
| `Kms_Driven` | Numerical | Total distance driven in kilometers |
| `Fuel_Type` | Categorical | Fuel variant (`Petrol`, `Diesel`, `CNG`) |
| `Seller_Type` | Categorical | Seller category (`Dealer`, `Individual`) |
| `Transmission` | Categorical | Gearbox type (`Manual`, `Automatic`) |

---

## 📈 Machine Learning Workflow
