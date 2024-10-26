# Customer Churn Analysis and Prediction

## Overview
This repository contains the code and resources for predicting customer churn using machine learning techniques. The goal of this project is to identify customers who are likely to stop using a service and provide insights to retain them.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Key Features](#key-features)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Analysis of Results](#analysis-of-results)
- [Requirements](#requirements)
- [How to Use](#how-to-use)
- [Future Work](#future-work)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Customer churn is a critical issue for many businesses, and predicting churn can help companies take proactive measures to retain customers. This project utilizes machine learning algorithms to predict customer churn and provides actionable insights.

## Dataset
The dataset used in this project contains customer information and their usage patterns. It includes features such as customer demographics, account information, and service usage.

### Data Description
- **CustomerID:** Unique identifier for each customer
- **Gender:** Gender of the customer (Male/Female)
- **SeniorCitizen:** Indicates if the customer is a senior citizen (1 for Yes, 0 for No)
- **Partner:** Indicates if the customer has a partner (Yes/No)
- **Dependents:** Indicates if the customer has dependents (Yes/No)
- **Tenure:** Number of months the customer has stayed with the company
- **PhoneService:** Indicates if the customer has phone service (Yes/No)
- **MultipleLines:** Indicates if the customer has multiple lines (Yes/No/No phone service)
- **InternetService:** Type of internet service (DSL/Fiber optic/No)
- **OnlineSecurity:** Indicates if the customer has online security (Yes/No/No internet service)
- **OnlineBackup:** Indicates if the customer has online backup (Yes/No/No internet service)
- **DeviceProtection:** Indicates if the customer has device protection (Yes/No/No internet service)
- **TechSupport:** Indicates if the customer has tech support (Yes/No/No internet service)
- **StreamingTV:** Indicates if the customer has streaming TV (Yes/No/No internet service)
- **StreamingMovies:** Indicates if the customer has streaming movies (Yes/No/No internet service)
- **Contract:** Type of contract (Month-to-month/One year/Two year)
- **PaperlessBilling:** Indicates if the customer has paperless billing (Yes/No)
- **PaymentMethod:** Payment method (Electronic check/Mailed check/Bank transfer (automatic)/Credit card (automatic))
- **MonthlyCharges:** Monthly charges for the customer
- **TotalCharges:** Total charges for the customer
- **Churn:** Indicates if the customer has churned (Yes/No)

## Key Features
- **Ease of Use:** Clear steps for data preprocessing, modeling, and evaluation.
- **Multiple Models:** Implementation of various machine learning algorithms for comparison.
- **Extensive EDA:** Comprehensive exploratory data analysis to understand the data.
- **Result Analysis:** Detailed analysis of model performance and insights.

## Data Preprocessing
Data preprocessing steps include handling missing values, encoding categorical variables, and scaling numerical features. Detailed preprocessing steps can be found in the [data_preprocessing.py](data_preprocessing.py) script.

## Exploratory Data Analysis
Exploratory Data Analysis (EDA) is performed to understand the distribution of data and the relationships between features. Visualizations and statistical summaries are provided in the [EDA notebook](notebooks/EDA.ipynb).

## Modeling
Various machine learning models are trained and evaluated to predict customer churn. The models include:
- Logistic Regression
- Decision Trees
- Random Forest
- Gradient Boosting
- Support Vector Machines

The modeling process is documented in the [modeling notebook](notebooks/modeling.ipynb).

## Evaluation
Model performance is evaluated using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC. The evaluation results are detailed in the [evaluation notebook](notebooks/evaluation.ipynb).

## Analysis of Results
The results of the best-performing model are presented, along with feature importance and insights derived from the model. Key findings include:
- **Feature Importance:** Identification of the most influential features contributing to customer churn.
- **Model Performance:** Comparison of different models based on evaluation metrics.
- **Customer Insights:** Actionable insights derived from the model to help in customer retention strategies.

## Requirements
- Python 3.6 or higher
- Required Python libraries are listed in `requirements.txt`:
    - pandas
    - numpy
    - scikit-learn
    - matplotlib
    - seaborn
    - jupyter

## How to Use
1. Clone the repository:
    ```bash
    git clone https://github.com/nikhilm21/Customer-Churn-Prediction.git
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the data preprocessing script:
    ```bash
    python data_preprocessing.py
    ```
4. Train the models and evaluate:
    ```bash
    python modeling.py
    ```
## Contributing
Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) for more information.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
