# 🏠 House Price Prediction (Per Unit Area)

This project predicts house prices (per unit area) in Taiwan based on key location features. The model is trained using a linear regression algorithm and includes an interactive web interface powered by Gradio.

## 🚀 Demo

📍 Try the app on [Kaggle](https://www.kaggle.com/code/rawsheed91/end-to-end-house-price-prediction-model/edit)

## 📊 Features Used

The model predicts the target value:

- **House price of unit area** (meters)

Based on the following features:

- `Distance to the nearest MRT station` (in meters)
- `Number of convenience stores` nearby
- `Latitude` (geographical coordinate)
- `Longitude` (geographical coordinate)

## ⚙️ Model

- **Algorithm**: Linear Regression
- **Library**: `scikit-learn`
## 🧪 Interactive UI (Gradio)

The app allows users to input values for each of the features and get an instant price prediction.

![gradio ui preview](![image](https://github.com/user-attachments/assets/798eb1b0-e654-487d-8eb3-127d43ea7d88)
) <!-- Optional: Add a screenshot of your UI -->

---

## 📁 Repository Structure

```bash
├── README.md
├── Real_Estate.csv           #Real Estate data  
├── model.pkl                 # Trained linear regression model               
├── notebook.ipynb           # Data exploration and training steps
              
