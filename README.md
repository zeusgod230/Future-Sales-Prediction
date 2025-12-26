# 📈 Future Sales Prediction using Linear Regression

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange.svg)
![Pandas](https://img.shields.io/badge/Library-Pandas-brightgreen.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

---

## 🎯 Overview

This project predicts **future product sales** based on advertising expenditure across three channels: **TV, Radio, and Newspaper**.  
Using historical data, a **Multiple Linear Regression** model is built to analyze the relationship between marketing spend and sales performance.

---

## 📊 Dataset Description

The dataset contains **200 observations** with the following features:

- **TV**: Advertising budget spent on TV (in thousands of dollars)
- **Radio**: Advertising budget spent on Radio
- **Newspaper**: Advertising budget spent on Newspaper
- **Sales**: Target variable representing units sold

> **Note:** During preprocessing, an outlier in **Row 93** (Sales value = 194) was identified and corrected to improve model reliability.

---

## 🚀 Features

- Data cleaning and outlier handling  
- Exploratory Data Analysis (EDA)  
- Multiple Linear Regression model  
- Model evaluation using **R² Score** and **Mean Squared Error (MSE)**  

---

## 🛠️ Installation & Setup

### Clone the repository
```bash
git clone https://github.com/zeusgod230/Future-Sales-Prediction.git
cd Future-Sales-Prediction
