# CreditWise: Machine Learning–Driven Credit Risk Assessment

## Overview

CreditWise is a machine learning project designed to predict loan eligibility and assess credit risk using historical financial data. The project builds a complete data science pipeline that includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and performance evaluation.

The goal of this project is to help financial institutions or lending platforms make data-driven decisions when approving or rejecting loan applications.

---

## Features

* Data preprocessing and cleaning (handling missing values and duplicates)
* Exploratory Data Analysis (EDA) with visualizations
* Feature encoding and feature engineering
* Correlation analysis using heatmaps
* Model training using multiple machine learning algorithms
* Model evaluation using performance metrics such as precision, recall, accuracy, and F1-score
* Identification of the best performing model for credit risk prediction

---

## Technologies Used

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical computing
* **Seaborn & Matplotlib** – Data visualization
* **Scikit-learn** – Machine learning models and preprocessing

---

## Machine Learning Models Used

The project trains and evaluates multiple models to determine the best performer:

* Naive Bayes
* Logistic Regression
* K-Nearest Neighbors (KNN)

After evaluation, **Naive Bayes** achieved the best performance based on precision and overall classification metrics.

---

## Project Workflow

1. **Data Collection**

   * Load dataset containing financial and credit-related attributes.

2. **Data Cleaning**

   * Handle missing values
   * Remove inconsistencies
   * Prepare dataset for analysis

3. **Exploratory Data Analysis**

   * Understand patterns in the dataset
   * Visualize relationships between variables
   * Correlation heatmap analysis

4. **Feature Engineering**

   * Encoding categorical variables
   * Scaling numerical features
   * Creating meaningful predictors

5. **Model Training**

   * Split dataset into training and testing sets
   * Train multiple machine learning models

6. **Model Evaluation**

   * Evaluate models using accuracy, precision, recall, and F1-score
   * Select the best-performing model

---

## Results

The **Naive Bayes classifier** provided the best balance between precision and recall for predicting loan approval and credit risk, achieving strong predictive performance compared to other models tested.

---

## Repository Structure

```
CreditWise/
│
├── credit_wise.ipynb      # Main notebook containing full pipeline
├── dataset/               # Dataset used for training and testing
├── README.md              # Project documentation
```

---

## Future Improvements

* Implement advanced models such as Random Forest or XGBoost
* Deploy the model as a web application
* Integrate real-time credit scoring APIs
* Improve feature engineering for higher predictive accuracy

---

## Author

**AbdulSamad**

If you found this project useful, feel free to ⭐ the repository.
