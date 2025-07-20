# Week 4 – Employee Attrition Prediction

🔍 This project is part of the **NSP Internship Program (Week 4)**. The objective is to analyze the IBM HR Analytics dataset and build a Machine Learning model to predict employee attrition.

---

## 📁 Dataset Used

- **Dataset Name**: IBM HR Analytics Employee Attrition & Performance
- **Source**: Kaggle
- **Link**: [IBM HR Analytics Dataset on Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

---

## 🎯 Objective

To understand the factors leading to employee attrition and build a machine learning model that predicts whether an employee is likely to leave the company.

---

## 🧪 Technologies & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Project Workflow

### 1. Data Loading and Exploration
- Loaded the dataset using pandas
- Checked for null values, data types, and initial stats

### 2. Data Preprocessing
- Handled categorical variables using Label Encoding
- Normalized numerical features
- Checked for class imbalance

### 3. Exploratory Data Analysis (EDA)
- Visualized relationships between features (e.g., Age vs Attrition, Job Role vs Attrition)
- Used count plots, heatmaps, histograms for insights

### 4. Model Building
- Split data into training and testing sets (80/20)
- Trained models:
  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest Classifier

### 5. Model Evaluation
- Used accuracy, precision, recall, F1-score
- Compared model performance
- Displayed confusion matrix

---

## ✅ Results

- **Best Model**: Random Forest Classifier
- **Accuracy**: ~85%
- **Important Features**:
  - OverTime
  - JobSatisfaction
  - EnvironmentSatisfaction
  - MonthlyIncome
  - Age

---

## 📌 Key Insights

- Employees working overtime are more likely to leave.
- Low job satisfaction and environment satisfaction are strong indicators of attrition.
- Young employees (age < 30) show higher attrition rates.

---


