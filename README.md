# Credit Card Fraud Detection

This project focuses on detecting fraudulent credit card transactions using machine learning models. The aim is to create a robust system that can identify fraudulent transactions with high accuracy and reliability, helping to mitigate financial losses.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Installation](#installation)

## Project Overview

Credit card fraud detection is a critical challenge in the financial sector. This project leverages supervised machine learning models to analyze transaction patterns and distinguish between fraudulent and legitimate transactions. 

### Key Features:
- **Preprocessing**: Addressed data imbalance with techniques like SMOTE.
- **Evaluation**: Assessed models using AUC-ROC, Precision, Recall, and F1-score.
- **Visualization**: Plotted key fraud patterns and model performance metrics for better insights.

## Dataset

The dataset used in this project is sourced from [Kaggle’s Credit Card Fraud Detection dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud). It contains anonymized features (`V1`, `V2`, ..., `V28`), transaction amount, and the target label (`Class`), where:
- `Class = 0`: Legitimate transaction
- `Class = 1`: Fraudulent transaction

## Technologies Used

- **Programming Languages**: Python  
- **Libraries/Frameworks**: Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn   
- **Development Tools**: Jupyter Notebook, GitHub  
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score, AUC-ROC  

## Installation

Follow these steps to set up the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/sumits234/credit_card_fraud_detection.git
   cd credit_card_fraud_detection
