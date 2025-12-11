🌫️ Air Quality Index Prediction – Machine Learning Project

This project applies Machine Learning techniques to predict Air Quality Index (AQI) and classify pollution levels using real pollutant data collected from the Government of India's open data portal (data.gov.in).
It demonstrates a complete end-to-end ML workflow including exploration, cleaning, feature engineering, modeling, evaluation, and prediction.

📌 Project Description

This project utilizes real-time air quality data consisting of numerical pollutant readings such as:

PM2.5

PM10

NO₂

SO₂

CO

O₃

AQI

Using these features, the models perform two tasks:

🔹 1. Regression:

Predict the AQI value based on pollutant concentrations.

🔹 2. Classification:

Classify AQI levels into pollution categories:

0 → Good

1 → Moderate

2 → Poor

3 → Very Poor

🔹 3. Additional ML Approach:

Random Forest Classifier for better performance and feature importance analysis.

This project is suitable for:

Students building ML portfolio projects

Academic submissions (including report & viva)

Anyone analyzing environmental data

GitHub portfolio enhancement

🗂️ Dataset Source

Official Government Dataset:
Real-Time Air Quality Index for various locations in India
🔗 https://www.data.gov.in/resource/real-time-air-quality-index-various-locations

🧠 Machine Learning Models Implemented
Model	Type	Purpose
Linear Regression	Regression	Predict actual AQI
Logistic Regression	Classification	Predict AQI category
Random Forest Classifier	Classification	Improve accuracy & handle non-linearity
🔧 Project Workflow

Import Libraries

Load Dataset

Data Exploration (EDA)

Automatic Numeric Column Selection

Data Cleaning & Handling Missing Values

Outlier Detection

Scaling using StandardScaler

Encoding Target Variable into Classes

Train-Test Split

Model Building (Regression & Classification)

Model Testing

Performance Evaluation

New Data Prediction

🧪 Technologies Used

Python

Pandas

NumPy

Matplotlib

Scikit-Learn

📁 Project Structure
Air-Quality-ML-Project/
│── air quality index.csv
│── ml_project_code.py
│── README.md
│── requirements.txt
│── images/ (optional screenshots)

▶️ How to Run the Project
1️⃣ Install dependencies
pip install -r requirements.txt

2️⃣ Run the ML script
python ml_project_code.py

3️⃣ View outputs

Console shows model performance

Predictions for new data

Regression comparison tables

Feature scaling and correlation insights

📊 Model Performance Metrics
Linear Regression

Mean Squared Error (MSE)

R² Score

Logistic Regression & Random Forest

Accuracy

Classification Report

Precision, Recall, F1 Score

(Random Forest generally performs the best.)

📈 Sample Prediction Output
Predicted Value (Linear Regression): 156.42
Predicted Class (Logistic Regression): 2
Predicted Class (Random Forest): 2

📝 Future Enhancements

Add a Streamlit dashboard

Build a Power BI visualization

Include more pollutants from API

Add hyperparameter tuning

Deploy model using Flask / FastAPI

👨‍💻 Author

Nikhil Ummadi
Machine Learning Enthusiast

⭐ Support

If you found this project useful, please ⭐ star the repository and share it!
