# House Prices Prediction (India)

## Project Overview

This project focuses on **predicting house prices in India** using classical machine learning techniques. There is data loading, brief exploratory analysis, feature selection, model training, and evaluation.

---

## Project Workflow

### 1. Data Loading & Inspection

* Loaded the dataset using **pandas**
* Inspected structure with `.head()`, `.tail()`, `.info()`, and `.describe()`
* Verified:

  * No null values
  * No duplicate records

### 2. Exploratory Data Analysis (EDA)

* Converted scientific notation outputs into readable price statistics
* Group-by aggregation
* Bar plot visualizations with **matplotlib**

### 3. Feature Selection

The following features were selected for modeling:

* Number of bedrooms
* Number of bathrooms
* Living area

Target variable:

* `price`

---

## Modeling

### Train-Test Split

* Used `train_test_split` from **scikit-learn**
* Split ratio:

  * 80% training
  * 20% testing

### Linear Regression

* Trained a **Linear Regression** model using selected features
* No feature scaling applied

---

## Model Evaluation

The model was evaluated using:

* **Mean Squared Error (MSE)**
* **Mean Absolute Error (MAE)**

These metrics provide insight into:

* Average prediction error magnitude (MAE)
* Penalization of larger errors (MSE)

---

## Technologies Used

* Python
* pandas
* matplotlib
* scikit-learn
* Jupyter Notebook

---

## Code Structure

* `housePriceLinearReg.ipynb` – Data loading, EDA, feature selection, linear regression modeling, and evaluation
* `House Price Indiacsv` – Dataset used for training and testing
