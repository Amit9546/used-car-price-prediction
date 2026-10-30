# Used Car Price Prediction using Linear Regression

This repository contains a complete end-to-end machine learning project that implements a **Linear Regression** model using Scikit-Learn to predict used car prices in INR based on various car specifications and features[cite: 2].

## 🚀 Project Overview
The goal of this project is to build a regression model that estimates the selling price of a used car by analyzing factors such as car age, kilometres driven, engine capacity, fuel type, and transmission type[cite: 2].

## 🛠️ Tech Stack & Libraries
* **Python**[cite: 2]
* **Pandas & NumPy** (Data loading, cleaning, and manipulation)[cite: 2]
* **Scikit-Learn** (Data preprocessing, encoding, normalization, model training, and evaluation)[cite: 2]
* **Jupyter Notebook**

## 📊 Data Preprocessing & Pipeline
1. **Categorical Encoding:** Applied `LabelEncoder` for transmission features and `OneHotEncoder` for fuel types[cite: 2].
2. **Feature Normalization:** Used Scikit-Learn's `Normalizer` to scale numerical features effectively[cite: 2].
3. **Train-Test Split:** Split the dataset into 70% training and 30% testing sets (`random_state=42`)[cite: 2].

## 📈 Model Performance & Metrics
The model is evaluated using standard regression performance metrics:
* **$R^2$ Score (Coefficient of Determination):** ~0.928[cite: 2]
* **Mean Squared Error (MSE):** ~2.21e-06[cite: 2]
* **Mean Absolute Error (MAE):** ~0.0010[cite: 2]

## 📂 Repository Structure
```text
├── Old_Car_Price_Prediction.ipynb   # Jupyter Notebook with full EDA, preprocessing, and model training
└── README.md                        # Project documentation
