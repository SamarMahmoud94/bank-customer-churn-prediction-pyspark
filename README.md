# Bank Customer Churn Prediction Using PySpark

## Project Overview

This project analyzes customer churn data using **PySpark** and builds a machine learning model using **Spark MLlib** to predict customer churn.

The project covers the complete data analysis and machine learning workflow, including data loading, data cleaning, validation, exploratory data analysis, feature engineering, model building, and evaluation.

## Technologies Used

* Python
* PySpark
* Apache Spark
* Spark MLlib
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

## Project Workflow

### 1. Spark Setup

* Created a SparkSession.
* Checked the Spark version.
* Configured the environment for PySpark.

### 2. Data Loading

* Loaded the Bank Customer Churn dataset into a Spark DataFrame.
* Inspected the dataset structure, schema, and sample records.
* Analyzed the number of records and features.

### 3. Data Cleaning & Validation

* Checked for missing values and invalid records.
* Validated important numerical and categorical fields.
* Performed data quality checks before model training.

### 4. Exploratory Data Analysis

* Analyzed customer characteristics and churn patterns.
* Used PySpark aggregations and grouping operations.
* Examined churn across different customer attributes.

### 5. Feature Engineering

* Prepared categorical features for machine learning.
* Applied categorical indexing and encoding.
* Assembled input features into a single feature vector.

### 6. Machine Learning

A machine learning pipeline was built using **Spark MLlib**.

The pipeline includes:

* Categorical feature indexing
* One-hot encoding
* Feature assembly
* Logistic Regression

### 7. Model Evaluation

The model was evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC

### Results

| Metric    |  Score |
| --------- | -----: |
| Accuracy  | 81.16% |
| Precision | 78.83% |
| Recall    | 81.16% |
| F1-Score  | 77.37% |
| ROC-AUC   |  0.762 |

## Project Structure

```text
bank-customer-churn-prediction-pyspark/
│
├── data/
│   └── bank_customer_churn.csv
│
├── notebooks/
│   └── bank_customer_churn_analysis.py
│
├── README.md
├── requirements.txt
└── .gitignore
```

## Key Skills Demonstrated

* PySpark Data Processing
* Data Cleaning & Validation
* Exploratory Data Analysis
* Feature Engineering
* Spark MLlib
* Machine Learning Pipelines
* Classification
* Model Evaluation
* Data Visualization
* SQL/Data Analysis Concepts
