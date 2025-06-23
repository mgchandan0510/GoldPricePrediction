# 📈 Gold Price Prediction

A machine learning model using Random Forest Regressor to predict the price of gold based on historical market data and related financial indicators.

## 🔍 Project Overview

This project involves building a predictive model using the **Random Forest Regression** algorithm to forecast gold prices. The dataset includes historical records with features like SPX, USO, SLV, and more, influencing the price of gold (GLD). The model is trained, evaluated using R² score, and visualized to compare predicted vs actual values.

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## 📁 Dataset

The dataset used is a CSV file named `gold_price_data.csv` which includes:
- Date
- SPX
- GLD (Gold Price)
- USO
- SLV
- ...other financial indicators

> 📌 Note: Replace `/content/gold_price_data.csv` with your own file path if you're running locally.

## 📊 Key Features

- Data preprocessing and exploration (handling nulls, shape, and summary statistics)
- Correlation analysis with heatmaps and distribution plots
- Feature-target splitting and data partitioning (Train/Test)
- Model training with RandomForestRegressor
- R² Score evaluation
- Visualization of actual vs predicted gold prices

## 🚀 How to Run the Project

1. **Clone the Repository**
   ```bash
   git clone https://github.com/mgchandan/GoldPricePrediction.git
   cd GoldPricePrediction
