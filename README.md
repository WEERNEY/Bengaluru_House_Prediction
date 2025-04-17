# 🏠 Bengaluru House Price Prediction

This project is a machine learning-based solution to predict house prices in **Bengaluru, India** using various real estate features. The objective is to build a regression model that accurately estimates house prices based on property attributes like location, size, number of bathrooms, and more.

---

## 📌 Project Overview

House price prediction is a crucial task for buyers, sellers, and investors. In this project, we analyze a real-world dataset from Bengaluru, preprocess and clean the data, build a machine learning model, and fine-tune it for better predictions.

---

## 📂 Dataset

The dataset used is the **Bengaluru House Price** dataset, which includes the following features:

- `location` – Area or locality of the property
- `size` – Number of bedrooms (e.g., 2 BHK, 4 Bedroom)
- `total_sqft` – Total area in square feet
- `bath` – Number of bathrooms
- `balcony` – Number of balconies
- `price` – Price of the property in lakhs (target variable)
- Other relevant attributes

---

## 🧰 Tools and Technologies

- **Python**
- **Pandas** – Data cleaning and manipulation
- **NumPy** – Numerical operations
- **Matplotlib / Seaborn** – Visualization
- **Scikit-learn** – Model building and evaluation

---

## 🚀 Project Workflow

### 1. Data Cleaning & Preprocessing
- Extracted numerical values from non-standard inputs (like `2 BHK` and `2100 - 2850` sqft)
- Removed outliers and inconsistent entries
- Converted text-based categorical data into numerical format
- Handled missing values in features like `bath` and `balcony`

### 2. Feature Engineering
- Created new features such as price per square foot
- Grouped rare locations into “other” to reduce noise

### 3. Model Building
- Implemented a **Decision Tree Regressor**
- Trained the model on processed data
- Evaluated using **Mean Absolute Error (MAE)**

### 4. Model Tuning
- Experimented with different `max_leaf_nodes` to find the best-performing tree
- Selected model configuration with the lowest MAE

---

## 📊 Model Performance

- **Evaluation Metric:** Mean Absolute Error (MAE)
- Tuned model provided better accuracy with optimal leaf node configuration

---

## 📁 Files in this Repository

- `HousePricePrediction.ipynb` – Jupyter Notebook with full code and analysis
- `bengaluru_house_prices.csv` – Dataset used in the project
- `README.md` – Project documentation

---

## ✅ Future Improvements

- Try advanced models like Random Forest, XGBoost, or Lasso Regression
- Use hyperparameter tuning with GridSearchCV
- Deploy the model with a user-friendly frontend using Streamlit or Flask

---

## ✨ Author

Made with ❤️ by Akshit Singh

