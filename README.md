# Customer Churn Prediction

This project aims to predict customer churn using a neural network implemented with TensorFlow. By analyzing customer data, we can identify patterns that indicate whether a customer is likely to leave or stay with the company. This information can be valuable for implementing retention strategies and improving customer satisfaction.

## Overview
Customer churn, also known as customer attrition, refers to the loss of clients or customers. This project uses a neural network to predict whether a customer will churn, helping businesses to retain customers and minimize revenue loss.

## Dataset
The dataset used in this project contains customer information, including demographics, account information, and service usage patterns. It can be found on [Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn) or any other similar source.

## Installation
To get started with this project, clone the repository and install the required dependencies.

```bash
git clone https://github.com/MirzaWaseem-Baig/Customer-Churn-Prediction.git
pip install matplotlib numpy pandas scikit-learn seaborn tensorflow
```

## Usage
1. Clone the repository and navigate to the project directory.
2. Install the required dependencies.
3. Run the Jupyter Notebook or Python script to preprocess the data, train the neural network, and make predictions.

```bash
jupyter notebook Customer Churn Prediction.ipynb
```

## Features
- **Data Preprocessing**: Handling missing values, encoding categorical variables, and scaling numerical features.
- **Exploratory Data Analysis (EDA)**: Visualizing the distribution of features and understanding the relationship between them and customer churn.
- **Model Training**: Training a neural network using TensorFlow to predict customer churn.
- **Model Evaluation**: Evaluating model performance using metrics like accuracy, precision, recall, and F1-score.

## Model Evaluation
The model is evaluated based on the following metrics:
- **Accuracy**: The ratio of correctly predicted instances to the total instances.
- **Precision**: The ratio of correctly predicted positive observations to the total predicted positives.
- **Recall (Sensitivity)**: The ratio of correctly predicted positive observations to all the observations in the actual class.
- **F1 Score**: The weighted average of Precision and Recall.

## Results
The classification report for the neural network model is as follows:

```
              precision    recall  f1-score   support

           0       0.80      0.90      0.85       999
           1       0.65      0.44      0.53       408

    accuracy                           0.77      1407
   macro avg       0.72      0.67      0.69      1407
weighted avg       0.76      0.77      0.75      1407
```

This indicates that the model has a good ability to predict non-churn customers (class 0) but struggles more with predicting churn customers (class 1).

## Contributing
Contributions are welcome! If you have any suggestions or improvements, please create an issue or submit a pull request.
