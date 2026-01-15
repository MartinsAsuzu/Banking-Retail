# Banking-Retail
## Optimizing Retail Banking Strategies Through RFM-Based Customer Segmentation
## Project Overview

This project applies RFM (Recency, Frequency, Monetary) analysis and unsupervised machine learning to segment retail banking customers based on transaction behavior.
The goal is to help a fictional bank, BankTrust, reduce customer churn, improve personalization, and make marketing efforts more effective using data-driven insights 
The project follows a full data science workflow, from data cleaning and feature engineering to clustering and business interpretation, with an optional deployment as an interactive Streamlit dashboard.

#Business Problem

Retail banks face several challenges:

Customer churn: Retaining existing customers is cheaper than acquiring new ones.

Lack of personalization: Generic products and messaging lead to disengagement.

Marketing inefficiency: Poor targeting increases costs and lowers ROI.

This project addresses these challenges by grouping customers into meaningful segments based on their transaction history, enabling targeted retention and marketing strategies 


#Why RFM Analysis?

RFM analysis segments customers using:

Recency: How recently a customer made a transaction

Frequency: How often they transact

Monetary: The total value of their transactions

By combining these metrics, banks can identify high-value customers, inactive customers, and those at risk of churn, allowing for timely and relevant interventions 


#Project Objectives

Segment customers using RFM metrics

Assign RFM scores and create interpretable customer groups

Apply unsupervised learning to uncover hidden customer patterns

Translate analytical results into clear business actions

(Enhancement) Build an interactive Streamlit dashboard for non-technical users 


#Dataset Description

The dataset contains anonymized retail banking transaction records, including:

TransactionID

CustomerID

CustomerDOB

CustGender

CustLocation

CustAccountBalance

TransactionDate

TransactionTime

TransactionAmount

These features are used to compute RFM metrics and support exploratory and segmentation analysis 


#Methodology

Exploratory Data Analysis (EDA)
Understanding data distributions, trends, and anomalies.

Feature Engineering

Calculate Recency, Frequency, and Monetary values

Assign RFM scores using quantiles

Create customer segments from combined RFM scores

Unsupervised Learning

Apply KMeans clustering on RFM features

Determine optimal cluster size using Elbow Method or Silhouette Score

Profile and interpret clusters

Business Interpretation
Translate customer segments into actionable strategies for retention, personalization, and marketing.

Project Enhancement (Optional)
Develop and deploy a Streamlit dashboard for interactive exploration and scenario testing 


#Tech Stack

Language: Python

Libraries:

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

Streamlit (for deployment)

#Repository Structure
├── data/                   # Raw and processed datasets
├── notebooks/              # Jupyter notebooks (EDA, RFM, clustering)
├── app/                    # Streamlit app files (if deployed)
├── requirements.txt        # Project dependencies
└── README.md               # Project documentation

#Key Outcomes

Clear customer segments such as high-value, loyal, at-risk, and inactive customers

Actionable insights to support targeted marketing and retention

A reusable framework for applying RFM analysis in financial services

Future Improvements

Integrate churn prediction models on top of RFM segments

Automate pipeline using scheduled data refresh

Extend dashboard with KPI tracking and executive summaries

Martins Nnaemeka Asuzu
Data Science | Analytics | Applied Machine Learning

