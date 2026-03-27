Predicting Myocardial Infarction Risk Using Machine Learning
Project Overview
This project focuses on predicting the risk of myocardial infarction (heart attack) using both supervised and unsupervised machine learning algorithms. The goal is to build predictive models that can identify individuals at higher risk based on clinical and demographic features.
The dataset used for this study contains 70,000 patient records and includes various health-related parameters relevant to cardiovascular risk assessment.
Objectives
Develop predictive models for myocardial infarction risk.
Compare the performance of multiple supervised machine learning algorithms.
Explore underlying patterns in the dataset using unsupervised clustering techniques.
Evaluate model performance using standard classification metrics.
Machine Learning Approaches
Supervised Learning Models
The following classification algorithms were implemented and evaluated:
Logistic Regression
Random Forest
Gradient Boosting
Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)
These models were trained to predict the probability of myocardial infarction based on input health features.
Unsupervised Learning Models
To explore hidden structures and groupings within the dataset, the following clustering algorithms were applied:
K-Means Clustering
DBSCAN (Density-Based Spatial Clustering of Applications with Noise)
Agglomerative Hierarchical Clustering
These techniques help identify natural clusters among patient profiles that may correspond to different cardiovascular risk patterns.
Dataset
Total Samples: 70,000 patient records
Type: Structured clinical dataset
Features include demographic and health-related variables relevant to cardiovascular disease risk.
Model Evaluation
The supervised models were evaluated using the following metrics:
Accuracy
Precision
Recall
F1-score
Classification Report
Tools and Technologies
Python
Pandas
NumPy
Scikit-learn
Google Colab
Project Goal
The project demonstrates how machine learning techniques can assist in early risk prediction and pattern discovery in cardiovascular health data, contributing to data-driven healthcare insights.
Repository Contents
Data preprocessing and feature engineering
Implementation of supervised learning models
Implementation of unsupervised clustering algorithms
Model evaluation and comparison
Visualization and analysis of results
