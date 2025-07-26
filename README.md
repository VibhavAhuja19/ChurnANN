# Customer Churn Prediction

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

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

### Prerequisites
- **Python 3.10**: This application requires Python 3.10 for TensorFlow compatibility
- **Model Format**: The model is saved in the `.keras` format (not `.h5`)

### Installation
1. Clone the repository:
```bash
git clone https://github.com/VibhavAhuja19/ChurnANN.git
cd ChurnANN

#### Run command

```bash
streamlit run app.py
```



