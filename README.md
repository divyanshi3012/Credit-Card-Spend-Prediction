# 💳 Credit Card Spend Prediction using Machine Learning

## 📌 Project Overview

This project presents an end-to-end Machine Learning solution for predicting customer credit card spending based on demographic, banking, and historical transaction data. The primary objective is to develop a regression model that can accurately estimate future credit card consumption, enabling data-driven business decisions.

The project covers the complete Machine Learning lifecycle, including data preprocessing, exploratory data analysis (EDA), feature engineering, model building, evaluation, and prediction generation.

---

## 🎯 Problem Statement

Understanding customer spending behavior is essential for financial institutions to optimize credit offerings, personalize customer experiences, and improve decision-making.

The objective of this project is to build a predictive regression model that estimates customer credit card spending using historical customer data and relevant financial attributes.

---

## 📂 Dataset

The dataset contains customer-related information, including:

* Customer demographics
* Banking details
* Historical credit card spending
* Monthly transaction information
* Target variable for credit card spend prediction

> **Note:** The dataset is not included in this repository due to privacy and licensing considerations.

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📊 Project Workflow

### 1. Data Collection & Understanding

* Imported datasets
* Explored dataset structure
* Examined data types and summary statistics

### 2. Data Preprocessing

* Handled missing values
* Removed duplicate records
* Treated outliers
* Prepared data for analysis

### 3. Exploratory Data Analysis (EDA)

* Univariate and bivariate analysis
* Correlation analysis
* Distribution visualization
* Feature relationship analysis

### 4. Feature Engineering

* Selected relevant features
* Encoded categorical variables
* Prepared data for model training

### 5. Model Development

* Built a Linear Regression model to predict customer credit card spending.

### 6. Model Evaluation

Performance was evaluated using:

* R² Score
* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* Mean Absolute Percentage Error (MAPE)

### 7. Prediction

Generated predictions for unseen customer data and exported the results as **`predicted_credit_consumption.csv`**.

---

## 🤖 Machine Learning Model

**Algorithm Used**

* Linear Regression

This model was used to establish the relationship between customer attributes and credit card spending, providing a reliable baseline for regression analysis.

---

## 📁 Repository Structure

```text
Credit-Card-Spend-Prediction/
│
├── Credit_Card_Consumption.ipynb        # Jupyter Notebook containing the complete ML workflow
├── CreditConsumptionData.xlsx           # Credit consumption dataset
├── CustomerBehaviorData.xlsx            # Customer behavior dataset
├── CustomerDemographics.xlsx            # Customer demographics dataset
├── Predicted_Credit_Consumption.csv     # Final predicted credit card spending
└── README.md                            # Project documentation
```

---

## 📌 Key Features

* Comprehensive data preprocessing
* Exploratory Data Analysis (EDA)
* Feature engineering
* Regression-based predictive modeling
* Model performance evaluation
* Prediction generation for unseen data
* Well-structured and reproducible workflow

---

## 🔮 Future Enhancements

* Compare multiple regression algorithms such as Random Forest, XGBoost, and Gradient Boosting.
* Perform hyperparameter tuning to improve model performance.
* Develop an interactive dashboard for visualization.
* Deploy the model as a web application using Flask or FastAPI.

---

## 👤 Author

**Divyanshi Singh**

**GitHub:** https://github.com/divyanshi3012

**LinkedIn:** https://www.linkedin.com/in/divyanshi-singh-82634a224
