Customer Churn Prediction

Project Overview

This academic team project uses machine learning to predict customer churn in a telecommunications company. It compares two classification models to identify customers who are likely to leave the service.

Dataset
## Source

- [Telco Customer Churn Dataset — Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
  
* Original records: 7,043
* Original features: 21
* Target variable: Churn
* Problem type: Binary Classification

Tools and Technologies

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn
* Kaggle Notebooks

Methodology

1. Explored the dataset using Pandas.
2. Converted TotalCharges to numeric format and handled 11 missing values.
3. Removed the customerID column.
4. Encoded categorical variables using One-Hot Encoding.
5. Split the data into training and testing sets using an 80/20 split.
6. Applied feature scaling using StandardScaler.
7. Trained and compared Logistic Regression and Random Forest classifiers.
8. Evaluated the models using Accuracy, Precision, Recall, F1-score, and confusion matrices.


## Results

| Model | Accuracy | Precision | Recall | F1-score |
|---|---:|---:|---:|---:|
| Logistic Regression | 80.38% | 64.76% | 57.49% | 60.91% |
| Random Forest | 78.82% | 62.34% | 51.34% | 56.30% |


Logistic Regression achieved higher scores across all four evaluation metrics in this experiment.

My Contribution

My individual contribution focused on initial data exploration and data cleaning, including inspecting the dataset with Pandas, checking for missing values and duplicates, converting TotalCharges to numeric format, and handling the resulting missing values.


## Project File
- [Customer Churn Prediction Notebook](./customer-churn-prediction.ipynb)

Note

This was an academic team project. To run the notebook outside Kaggle, download the dataset and update the file path as needed.
