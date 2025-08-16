# 🧠 Parkinson's Disease Detection using Machine Learning  

---

## 📌 Project Overview  
This project focuses on building a **Machine Learning model** to detect **Parkinson's Disease** using vocal features.  
The dataset is taken from [Kaggle - Parkinson’s Disease Dataset](https://www.kaggle.com/datasets/debasisdotcom/parkinsons-disease-detection).  
The main goal is to analyze biomedical voice features and classify whether a patient has Parkinson’s disease.  

---

## 📂 Dataset  
- **Source**: Kaggle  
- **Rows**: 195 samples  
- **Columns**: 22 biomedical voice measurements  
- **Target Variable**:  
  - `status = 1` → Patient has Parkinson’s  
  - `status = 0` → Healthy individual  

---

## ⚙️ Technologies Used  
- Python 🐍  
- Pandas, NumPy → Data Processing  
- Matplotlib, Seaborn → Data Visualization  
- Scikit-learn → Machine Learning Models  

---

## 📊 Exploratory Data Analysis (EDA)  
- ✅ Feature distribution plots  
- ✅ Correlation Heatmap (to check relationships)  
- ✅ Boxplots (to detect outliers)  
- ✅ Class distribution visualization  

---

## 🤖 Machine Learning Models Implemented  
- Logistic Regression  
- Support Vector Machine (SVM)  
- Random Forest Classifier  
- K-Nearest Neighbors (KNN)  

**Evaluation Metrics**:  
- Accuracy Score  
- Confusion Matrix  
- Classification Report  

---

## 🚀 Results  
- **Best Model**: Support Vector Machine (SVM) / Random Forest  
- **Accuracy Achieved**: ~87–90%  
- **Important Features**:  
  - `MDVP:Fo(Hz)`  
  - `MDVP:Jitter(%)`  
  - `MDVP:Shimmer`  
  - `HNR`  

---

## 📷 Sample Visualizations  
- 📌 Correlation Heatmap  
- 📌 Feature Distributions  
- 📌 Confusion Matrix Heatmap  

---

## 🏗️ How to Run Locally  

1️⃣ Clone this repository  
```bash
git clone https://github.com/your-username/parkinsons-disease-detection.git
cd parkinsons-disease-detection
