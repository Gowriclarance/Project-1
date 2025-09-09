PROJECT - CUSTOMER CHURN ANALYSIS & PREDITION

Summary

Customer churn is when users discontinue a service. For a telecom company, retaining existing customers is far cheaper than finding new ones.

This project is built using the Telco Customer Churn dataset by IBM. It contains detailed information of 7,043 customers, including:

Demographic info (gender, age group)

Service details (internet, phone, tech support, streaming)

Account details (contract type, billing, charges)

And finally, whether they have churned or not.

Dataset Info

Name: WA_Fn-UseC_-Telco-Customer-Churn.csv

Rows: 7,043 customer records

Target column: Churn (Yes/No)

Prediction type: Binary Classification (Will churn or not)

------------> Problem Statement

Can we use the available data to predict if a customer is likely to churn, and if so, why? How can we help the company take early action to prevent losing such customers?

TO UPLOAD DATASET 
from google.colab import files
uploaded = files.upload()


