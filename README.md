#Online Payments Fraud Detection

#Introduction

With the rapid growth of digital payment systems, online transactions have become an essential part of daily life. However, this growth has also led to an increase in online payment fraud, causing significant financial losses to individuals and organizations. Detecting fraudulent transactions manually is difficult due to the large volume of transactions generated every second.

Machine Learning provides an effective solution by analyzing transaction patterns and identifying suspicious activities automatically. This project focuses on building a machine learning–based fraud detection system that predicts whether an online payment transaction is fraudulent or legitimate. The system uses historical transaction data and applies classification techniques to detect fraud with high accuracy.

The developed system is deployed using Flask as a web application, allowing users to enter transaction details and receive real-time fraud predictions. This approach helps improve transaction security, reduce financial risk, and enhance trust in digital payment platforms.

#Project Overview

Online payment fraud is a major issue in digital transactions. This project uses Machine Learning to predict whether an online payment transaction is fraudulent or legitimate. The system is deployed using Flask and provides a web-based interface for real-time fraud prediction.

#Objectives
Detect fraudulent online payment transactions
Reduce financial loss due to fraud
Provide a user-friendly web interface
Apply machine learning classification techniques
#Machine Learning Approach
Algorithm Used: Random Forest Classifier
Problem Type: Binary Classification
Target Variable: isFraud (1 – Fraudulent, 0 – Legitimate)
#Dataset Description
Dataset Name: PaySim Dataset
Source: Kaggle

The dataset is a synthetic representation of real-world mobile money transactions.
step – Time step of transaction
type – Type of transaction
amount – Transaction amount
oldbalanceOrg – Sender balance before transaction
newbalanceOrig – Sender balance after transaction
oldbalanceDest – Receiver balance before transaction
newbalanceDest – Receiver balance after transaction
#Technologies Used
Python
Flask
Scikit-learn
HTML, CSS
Git & GitHub
#Application Workflow
1.User opens the Home page
2.Clicks on Start Prediction
3.Enters transaction details
4.Machine learning model processes the input
5.Prediction result is displayed to the user
#Results
The Random Forest model achieves good accuracy and successfully identifies fraudulent transactions. The system provides reliable real-time predictions through a simple web interface.
