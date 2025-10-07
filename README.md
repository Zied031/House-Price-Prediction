# 🏡 House Price Prediction - AI/ML Project

Welcome! 👋 This project is about building a **machine learning model** that can **predict house prices** based on different features like size, location, number of rooms, and more.

We use a real dataset from a Kaggle competition and apply various steps — from exploring the data to building and testing different ML models — to find the best way to predict prices.

---

## 🧠 What You'll Learn

* How to explore and understand a dataset
* How to clean and prepare data for machine learning
* How to try different ML models and choose the best one
* How to use the final model to make predictions

---

## 📦 Dataset

We use the dataset from the Kaggle competition:
👉 [House Prices - Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

* This dataset contains information about houses sold in Ames, Iowa.
* Our best model achieved an **87.16% accuracy** (R² score).

---

## 🗂️ Project Files

| File                           | Description                                                                       |
| ------------------------------ | --------------------------------------------------------------------------------- |
| `house_price_prediction.ipynb` | Jupyter Notebook with all the code (data loading, analysis, model training, etc.) |
| `submission.csv`               | Final predictions for house prices (used for Kaggle submission)                   |
| `gbr.pkl`                      | Saved trained model (Gradient Boosting Regressor) to use later without retraining |

---

## 🧰 Tools & Libraries Used

This project uses Python and these popular libraries:

* `NumPy` and `Pandas` – for data handling
* `Matplotlib` and `Seaborn` – for visualizing the data
* `Scikit-learn` – for building and testing ML models
* `XGBoost` – for advanced regression modeling

If you're new to any of these, don’t worry — this is a great project to start learning them!

---

## 🔍 Step-by-Step Overview

### 1. Load and Explore the Data

* We load the data from CSV files.
* Visualizations like histograms, box plots, and heatmaps help us understand:

  * Which features affect price the most
  * Where the data is missing
  * How the data is distributed

### 2. Preprocess the Data

* Handle missing values by filling them in or removing them
* Convert text categories (like "House Style") into numbers using **one-hot encoding**
* Standardize numerical data so everything is on the same scale

### 3. Train Different Models

We tried multiple regression models, including:

* Linear Regression
* Support Vector Regression (SVR)
* Random Forest
* Gradient Boosting (our final choice!)
* XGBoost
* and more...

We used **cross-validation** to test each model and picked the one with the best accuracy.

### 4. Make Predictions

* We trained our final model on the full training data
* Used it to predict prices on the test data
* Saved the predictions in a file: `submission.csv`

---

## 💾 Output Files

* **`submission.csv`** — Predicted prices for the test houses
* **`gbr.pkl`** — Saved ML model (you can load this later to make predictions without retraining)

---

## 📬 Questions or Feedback?

Feel free to reach out or suggest improvements!
Connect with me on [LinkedIn](https://www.linkedin.com/in/nirdesh-devadiya-55b408209)
