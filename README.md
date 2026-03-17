# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview

This project focuses on building a **Machine Learning regression model** to predict house prices based on various features such as size, number of rooms, location factors, and other property-related attributes.

The goal is to analyze the dataset, preprocess it, apply different regression models, and evaluate their performance to find the most accurate predictor.

---

## 🎯 Objectives

* Understand and explore the housing dataset
* Perform data preprocessing (handling missing values, duplicates, outliers)
* Conduct Exploratory Data Analysis (EDA)
* Apply feature engineering techniques
* Train regression models
* Evaluate and compare model performance

---

## 📂 Dataset

The dataset contains housing-related features such as:

* Area / Size of house
* Number of bedrooms & bathrooms
* Lot size
* Garage size
* Year built
* Neighborhood quality
* Target variable: **House_Price**

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn

---

## 🔄 Project Workflow

### 1. Data Loading

* Imported dataset using Pandas

### 2. Data Preprocessing

* Handled missing values
* Removed duplicate records
* Detected and treated outliers using IQR

### 3. Exploratory Data Analysis (EDA)

* Univariate analysis (histograms)
* Bivariate analysis (pairplots)
* Correlation heatmap

### 4. Feature Engineering

* Label Encoding for categorical variables
* Log transformation for skewed data
* Feature scaling using StandardScaler

### 5. Model Building

Two regression models were trained:

* Linear Regression
* K-Nearest Neighbors (KNN) Regression

### 6. Model Evaluation

Models were evaluated using:

* MAE (Mean Absolute Error)
* MSE (Mean Squared Error)
* RMSE (Root Mean Squared Error)
* MAPE (Mean Absolute Percentage Error)
* R² Score
* Adjusted R² Score

---

## 📊 Results

* Linear Regression provides a baseline model
* KNN captures non-linear relationships
* Performance comparison helps select the best model

---

## 🚀 How to Run the Project

1. Clone the repository:

```
git clone https://github.com/your-username/house-price-prediction.git
```

2. Navigate to the project folder:

```
cd house-price-prediction
```

3. Install required libraries:

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

4. Run the notebook or script:

```
python main.py
```

or open in Google Colab

---

## 📈 Future Improvements

* Use advanced models (Random Forest, XGBoost)
* Hyperparameter tuning
* Deploy model using Flask/Streamlit
* Add more real-world features
* 
---

## 👨‍💻 Author

**Nitya**

---

## ⭐ Acknowledgment

This project was developed as part of a Machine Learning assignment to understand regression techniques and real-world data analysis.

---
