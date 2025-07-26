# Customer Churn Prediction

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

A machine learning web application built with Streamlit and TensorFlow to predict customer churn probability based on various customer attributes.

## Table of Contents
- [Overview](#-overview)
- [Features](#-features)
- [Technologies Used](#-technologies-used)
- [Setup and Installation](#-setup-and-installation)
- [Required Files](#-required-files)
- [How to Use](#-how-to-use)
- [Model Information](#-model-information)
- [Troubleshooting](#-troubleshooting)
- [License](#-license)

## 📋 Overview

This application uses a trained deep learning model to predict whether a customer is likely to leave a service (churn) based on demographic and account information. The model analyzes factors such as:

- Credit score
- Geography
- Gender
- Age
- Account balance
- Estimated salary
- Tenure
- Number of products
- Credit card status
- Active member status

The application provides a churn probability estimate to help businesses identify at-risk customers.

## 🚀 Features

- **Interactive Web Interface**: Built with Streamlit for seamless user experience
- **Real-time Predictions**: Instant churn probability calculations
- **Comprehensive Input Options**:
  - Geography (Country selection)
  - Gender (Male/Female)
  - Age (Slider input)
  - Account balance
  - Credit score
  - Estimated salary
  - Tenure (Years with company)
  - Number of products
  - Credit card status (Yes/No)
  - Active member status (Yes/No)
- **Visual Prediction Results**: Clear output with probability percentage
- **Actionable Recommendations**: Suggestions based on prediction results

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python 3.10 | Core programming language |
| TensorFlow | Deep learning framework |
| Streamlit | Web application UI |
| Scikit-learn | Data preprocessing |
| NumPy | Numerical operations |
| Pandas | Data manipulation |
| Pickle | Model serialization |

## ⚙️ Setup and Installation

### Prerequisites

- Python 3.10 (required for TensorFlow compatibility)
- Git (for cloning the repository)

### ▶️ Quick Start
1. Clone and install dependencies:
```bash
git clone https://github.com/VibhavAhuja19/ChurnANN.git
cd ChurnANN
pip install -r requirements.txt

### Run Command
```bash
streamlit run app.py



