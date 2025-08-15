# 🏡 Housing Price Prediction – End-to-End ML Project

[![Python](https://img.shields.io/badge/python-3.11-blue)](https://www.python.org/)
[![License](https://img.shields.io/badge/license-Educational-lightgrey)](LICENSE)

An **end-to-end machine learning project** for predicting California house prices using the dataset from [Hands-On ML by Aurélien Géron](https://raw.githubusercontent.com/ageron/handson-ml/master/datasets/housing/housing.csv).

---

## Project Overview

This project demonstrates a **full ML workflow**, including:

- Data acquisition and exploration
- Data preprocessing and feature engineering
- Training multiple regression models
- Evaluation and comparison of model performance
- Saving/loading trained models for future predictions

The main goal is to predict the **median house value** based on features like income, rooms, population, and proximity to the ocean.

---

## Dataset

Dataset is directly available from:

https://raw.githubusercontent.com/ageron/handson-ml/master/datasets/housing/housing.csv

Contains features such as:

- `median_income`, `total_rooms`, `housing_median_age`, `ocean_proximity`, etc.  
- Target: `median_house_value`

---

## Project Structure
housing_price/

│

├── End-to-End-project.ipynb # Full ML pipeline in Jupyter Notebook

├── datasets/

│ └── housing/ # Housing dataset files

├── models/ # Trained models (ignored in GitHub)

├── README.md # Project description

└── .gitignore # Git ignore settings

> **Note:** The `models/` folder is excluded from GitHub due to large file sizes.

---

