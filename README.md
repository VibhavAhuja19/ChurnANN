# Customer Churn Prediction

A machine learning web application built with Streamlit and TensorFlow to predict customer churn probability based on various customer attributes.

## 📋 Overview
This application uses a trained deep learning model to predict whether a customer is likely to leave a service (churn) based on demographic and account information. The model analyzes factors such as credit score, geography, gender, age, balance, and other features to provide a churn probability estimate.

## 🚀 Features
- Interactive web interface built with Streamlit
- Real-time prediction of customer churn probability
- Support for various customer attributes:
  - Geography
  - Gender
  - Age
  - Account balance
  - Credit score
  - Estimated salary
  - Tenure
  - Number of products
  - Credit card status
  - Active member status
- Clear visualization of prediction results

## 🛠️ Technologies Used
- **Python**: Core programming language
- **TensorFlow**: Deep learning framework for the prediction model
- **Streamlit**: Web application framework
- **Scikit-learn**: For data preprocessing and encoding
- **NumPy & Pandas**: For data manipulation
- **Pickle**: For model serialization and deserialization

## ⚙️ Setup and Installation

### Important Requirements
- **Python 3.10**: This application requires Python 3.10 for TensorFlow compatibility
- **Model Format**: The model is saved in the `.keras` format (not `.h5`)

### Installation Steps
1. Make sure you have Python 3.10 installed:
   ```bash
   python --version
