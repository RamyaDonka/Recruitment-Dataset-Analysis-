# 📊 Recruitment Dataset Analysis (Income Classification)

##  Overview
This project focuses on building a machine learning model to classify individuals based on their income level (**<=50K or >50K**) using demographic and socio-economic features. The goal is to support data-driven decision-making for policy planning, resource allocation, and workforce analysis.

---

## 🎯 Problem Statement
To build a reliable classification model that predicts the income class of individuals, a comprehensive approach is followed including:

- Data collection  
- Data preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature engineering  
- Model building  
- Validation  

The model aims to accurately classify individuals into income groups (**<=50K** or **>50K**), which can help organizations and government bodies in:
- Policy planning  
- Resource allocation  
- Risk assessment  
- Demographic analysis  

---

## 📊 Dataset
The dataset contains demographic and employment-related features such as:
- Age  
- Education  
- Marital Status  
- Occupation  
- Capital Gain  
- Capital Loss  
- Hours per week  

---

## 🧠 Methodology

### 🔹 Data Preprocessing
- Handled missing values  
- Encoded categorical variables  
- Standardized data  

---

### 🔹 Exploratory Data Analysis (EDA)
- Identified key patterns and relationships  
- Visualized income distribution across features  

---

### 🔹 Model Development
- Built Decision Tree models using:
  - **Gini Index**
  - **Gain Ratio**

---

### 🔹 Model Evaluation
Models were evaluated using:
- Accuracy  
- Specificity  
- Sensitivity  
- AUC Score  
- Kappa Score  

---

## 📈 Results

### Decision Tree Model Comparison

| Metric        | Gini Index | Gain Ratio |
|--------------|-----------|-----------|
| Accuracy     | 0.8376    | 0.8380    |
| Specificity  | 0.9488    | 0.9483    |
| AUC Score    | 0.8245    | 0.8266    |
| Kappa        | 0.4970    | 0.4992    |
| Sensitivity  | 0.4888    | 0.4921    |

👉 The **Gain Ratio-based model performed slightly better** compared to the Gini Index model.

---

## 📊 Key Insights
- **Capital Gain, Marital Status, and Education** are the most influential features  
- Gain Ratio provides better model efficiency than Gini Index  
- Model achieves ~**83% accuracy**, indicating strong predictive performance  
- High specificity (~94%) shows effective identification of higher income group  

---

## 💡 Business Impact
- Helps identify income distribution patterns  
- Supports policy-making and economic planning  
- Enables targeted welfare and employment strategies  

---

## 🛠 Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  
- Jupyter Notebook  

---
