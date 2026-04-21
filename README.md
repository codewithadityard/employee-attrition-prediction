Emplyee Attrition Prediction 
---

## 📌 Project Overview
Employee attrition is a major cost for organizations. This project analyzes HR data to identify key drivers of employee turnover and builds a machine learning model to predict which employees are at risk of leaving.

The project combines **EDA, visualization, and classification models** to convert raw data into actionable business insights.

---

## 🎯 Problem Statement
High attrition leads to:
- Increased hiring costs  
- Loss of experienced employees  
- Reduced productivity  

This project aims to:
👉 Predict attrition  
👉 Identify key risk factors  
👉 Help HR teams take proactive action  

---

## 📊 Exploratory Data Analysis & Insights

Key analysis performed:

- **Histograms** → Distribution of age, income, experience   
- **Bar Charts** → Attrition trends across categories  
- **Line Plots** → Salary growth vs experience  
- **Pie Charts** → Overtime impact  
- **Heatmaps** → Feature correlation & redundancy  

### 🔥 Key Insights
- Overtime strongly increases attrition risk  
- Low satisfaction = high probability of leaving  
- Salary stagnation contributes to attrition  
- Certain job roles show higher turnover  

---

## ⚙️ Machine Learning Pipeline

### Data Preprocessing
- Removed unnecessary columns (e.g., EmployeeCount)
- Handled categorical features
- Avoided data leakage

### Handling Imbalance
- Dataset imbalance: **85% Stay / 15% Leave**
- Used **SMOTE** on training data only

### Models Used
- Decision Tree (baseline)
- Random Forest
- XGBoost (best performance)

### Evaluation
- Accuracy 84%
- Confusion Matrix  
- Classification Report  
- Focus on **Recall** (important for attrition prediction)

---

## 📈 Results & Business Impact

- Identified major drivers of employee attrition  
- Built predictive model to flag high-risk employees  
- Model can help HR teams:
  - Reduce attrition  
  - Improve retention strategies  
  - Take preventive action  

---

## ⚠️ Challenges Faced

- Severe class imbalance  
- Risk of data leakage  
- Feature redundancy  

### Solutions
- Applied SMOTE correctly  
- Used stratified splitting  
- Removed correlated features  

---

## 💻 Tech Stack

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Imbalanced-learn (SMOTE)  
- XGBoost  

---

## 📂 Project Structure

