# Online Payment Fraud Detection Project

![License](https://img.shields.io/badge/license-MIT-blue.svg)

This repository contains the code and documentation for the Online Payment Fraud Detection project. The goal of this project is to build a machine learning model that can predict online payment fraud.

## Problem Definition

Online payment fraud is a significant concern for financial institutions and businesses that operate in the digital payment space. Fraudulent transactions can result in financial losses, damage to reputation, and compromised customer trust. Detecting and preventing fraud in real-time is crucial to mitigate these risks.

The problem addressed in this project is to develop a machine learning model that can accurately classify online payment transactions as fraudulent or non-fraudulent based on various transaction attributes. By analyzing historical transaction data, we aim to identify patterns and features that can differentiate between legitimate and fraudulent transactions. The ultimate objective is to build a model that can effectively detect fraudulent transactions, thereby enabling timely action to prevent financial losses and protect customers.

## Project Overview

In this project, we aim to develop a machine learning model to detect online payment fraud. The dataset used for this project includes various features such as transaction type, amount, balances, and recipient information. By analyzing these features, we aim to train a model that can accurately classify transactions as fraudulent or non-fraudulent.

## Project Steps

1. Exploratory Data Analysis (EDA): Conducted exploratory data analysis to understand the distribution of the data, visualize relationships between variables, and identify any correlations.

2. Feature Engineering: Performed feature engineering to preprocess and transform the data. This included encoding categorical variables, creating new features, and handling missing values if applicable.

3. Model Selection, Training, and Validation: Trained and tested several supervised learning models, including Decision Tree, Random Forest, and K-Nearest Neighbors. Evaluated the performance of each model using relevant metrics.

4. Model Evaluation: Analyzed the results of the trained models and compared their performance. Considered metrics such as accuracy, precision, recall, F1-score, and ROC-AUC to assess the effectiveness of each model.

5. Model Deployment: Selected the best-performing model and deployed it for future predictions on new data.

## Repository Structure

- `notebooks/`: Jupyter notebooks with the code for data analysis, feature engineering, and model training.
- `README.md`: This file, providing an overview of the project.

## Dependencies

The project code is written in Python and utilizes the following libraries:

- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Usage

To run the project code, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Open and run the Jupyter notebooks in the `notebooks/` directory in sequential order.

## Results and Discussion

The best-performing model in terms of accuracy, precision, recall, F1-score, and ROC-AUC was the Random Forest algorithm. It demonstrated higher performance compared to the Decision Tree and K-Nearest Neighbors algorithms. The feature importance analysis indicated that the transaction amount, old and new balances, and transaction type were influential in predicting fraudulent transactions.

## Conclusion

This project highlights the development of a machine learning model for online payment fraud detection. The implemented model shows promising results in accurately identifying fraudulent transactions. The project's code, documentation, and findings can be utilized for further improvements and real-world implementation.

Please note that the dataset used for this project is fictitious and does not represent real-world transactions.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
