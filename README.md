Customer Churn Prediction

A machine learning web application built with Streamlit and TensorFlow to predict customer churn probability based on various customer attributes.

📋 Overview
This application uses a trained deep learning model to predict whether a customer is likely to leave a service (churn) based on demographic and account information. The model analyzes factors such as credit score, geography, gender, age, balance, and other features to provide a churn probability estimate.

🚀 Features
Interactive web interface built with Streamlit
Real-time prediction of customer churn probability
Support for various customer attributes:
Geography
Gender
Age
Account balance
Credit score
Estimated salary
Tenure
Number of products
Credit card status
Active member status
Clear visualization of prediction results
🛠️ Technologies Used
Python: Core programming language
TensorFlow: Deep learning framework for the prediction model
Streamlit: Web application framework
Scikit-learn: For data preprocessing and encoding
NumPy & Pandas: For data manipulation
Pickle: For model serialization and deserialization
⚙️ Setup and Installation
Important Requirements
Python 3.10: This application requires Python 3.10 for TensorFlow compatibility
Model Format: The model is saved in the .keras format (not .h5)
Installation Steps
Make sure you have Python 3.10 installed:

python --version
If not, download and install it from python.org
Clone this repository:

git clone https://github.com/yourusername/customer-churn-prediction.git
cd customer-churn-prediction
Install required dependencies:

pip install -r requirements.txt
Run the Streamlit application:

streamlit run app.py
📦 Required Files
Make sure the following files are available in your project directory:

model.keras: The trained TensorFlow model (must use .keras format, not .h5)
label_encoder_gen.pkl: Pickle file for gender label encoding
onehot_encoder_geo.pkl: Pickle file for geography one-hot encoding
scaler.pkl: Pickle file for feature scaling
🧪 How to Use
Open the web application in your browser
Input customer information using the provided fields and sliders
Click the "Predict" button to get the churn probability
Review the prediction result and recommendation
📊 Model Information
The prediction model is built using TensorFlow and is trained on historical customer data. It predicts the probability of customer churn based on various features. The model uses:

Standard scaling for numerical features
Label encoding for gender
One-hot encoding for geography
🔍 Troubleshooting
If you encounter issues loading the model, ensure you're using the correct TensorFlow version compatible with Python 3.10
Verify that all required pickle files are in the correct format and accessible
For model loading issues, confirm you're using model.keras format as specified in the code
