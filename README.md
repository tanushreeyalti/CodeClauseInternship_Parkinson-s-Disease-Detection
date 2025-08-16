🧠 Parkinson's Disease Detection using Machine Learning
📌 Project Overview

This project focuses on building a Machine Learning model to detect Parkinson's Disease using vocal features. The dataset is taken from Kaggle - Parkinson’s Disease Dataset.
The aim is to analyze patterns in voice recordings and classify whether a patient has Parkinson’s disease.

📂 Dataset

Source: Kaggle

Features: 22 biomedical voice measurements (e.g., fundamental frequency, jitter, shimmer, NHR, HNR)

Target: status (1 = Parkinson’s, 0 = Healthy)

Rows: 195 samples

⚙️ Technologies Used

Python

Pandas, NumPy (Data Processing)

Matplotlib, Seaborn (Visualization)

Scikit-learn (ML Models)

📊 Exploratory Data Analysis (EDA)

Histograms and distribution plots of features

Correlation Heatmap to identify important features

Boxplots to detect outliers

Class distribution visualization

🤖 Machine Learning Models

Logistic Regression

Support Vector Machine (SVM)

Random Forest Classifier

K-Nearest Neighbors (KNN)

Evaluation Metrics:

Accuracy

Confusion Matrix

Classification Report

🚀 Results

Best performing model: SVM / Random Forest

Achieved ~87–90% accuracy on test data

Key features: MDVP:Fo(Hz), MDVP:Jitter(%), MDVP:Shimmer, HNR

📷 Sample Visualizations

Correlation Heatmap

Feature Distributions

Confusion Matrix Heatmap
