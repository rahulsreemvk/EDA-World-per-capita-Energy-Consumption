# 🌍 Global Per Capita Energy Consumption  
### Exploratory Data Analysis & Linear Regression Modeling (1965–2019)

## 📌 Project Overview

This project explores global per-capita energy consumption trends from 1965 to 2019 using exploratory data analysis (EDA) techniques and a simple linear regression model.

The objective is to:

- Analyze long-term global energy consumption trends
- Compare energy usage patterns across countries
- Identify distribution characteristics and outliers
- Demonstrate a basic regression modeling workflow

This project is intended as a data analysis and portfolio project.

---

## 📊 Dataset

The dataset contains:

- **Entity** – Country name  
- **Code** – ISO country code  
- **Year** – Observation year  
- **Energy consumption per capita (kWh)**  

Time Range: **1965 – 2019**  
Total Records: **8,961**

Open dataset published by *Our World in Data*, which is frequently redistributed via Kaggle.

If reusing the dataset, please verify original attribution.

---

## 🛠 Technologies Used

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## 📈 Exploratory Data Analysis

The notebook includes:

- Data inspection and summary statistics
- Missing value analysis
- Distribution visualization
- Country-level comparisons
- Time-series trend analysis
- Correlation heatmaps
- Outlier exploration

Key observations include:

- Global per-capita energy consumption has increased over time.
- Significant variation exists across countries.
- The distribution is right-skewed due to high-consumption economies.
- Long-term upward trends dominate historical data.

---

## 🤖 Machine Learning Component

A simple **Linear Regression** model is implemented to:

- Explore relationships between year and energy consumption
- Demonstrate model training and evaluation
- Calculate Mean Squared Error (MSE)

This model is exploratory and intended for demonstration purposes only.  
It is not optimized for forecasting or production deployment.

---

## 🚀 How to Run the Project

Clone the repository:

```bash
git clone https://github.com/rahulsreemvk/EDA-World-per-capita-Energy-Consumption.git
cd EDA-World-per-capita-Energy-Consumption
