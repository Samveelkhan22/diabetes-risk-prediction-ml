# Diabetes Risk Prediction using Machine Learning

This repository contains a complete machine learning pipeline to analyze and predict diabetes risk using health indicators from a structured dataset. The project applies various classification algorithms to identify key predictors and assess model performance, aiming to support early diagnosis and personalized intervention strategies.

---

## 📌 Project Objectives

- Identify significant health-related risk factors for diabetes.
- Build predictive models using machine learning techniques.
- Evaluate model performance using metrics like accuracy, precision, recall, and F1 score.
- Visualize patterns and correlations in the data through EDA (Exploratory Data Analysis).

---

## 📊 Dataset Overview

- **Source**: Healthcare-Diabetes.csv (Kaggle public dataset)
- **Size**: 2768 records
- **Features**:
  - Id 
  - Pregnancies
  - Glucose
  - BloodPressure
  - SkinThickness
  - Insulin
  - BMI
  - DiabetesPedigreeFunction
  - Age
  - Outcome (0 = No Diabetes, 1 = Diabetes)


---

## 📅 Data Exploration & Visualization

- No missing values across all features.
- Visualizations included:
  - **Histograms** and **box plots** for all numeric features
  - **Scatter plots** to analyze relationships (e.g., Glucose vs. BMI)
  - **Correlation heatmap** to explore variable associations
  - **Line graph** showing Glucose trends across IDs

### Key Observations:
- Glucose, BMI, and Age showed strong correlation with diabetes.
- Some features (e.g., SkinThickness, Insulin) had high variance and outliers.
- The dataset had a diabetes prevalence rate of ~34.4%.

---

## 🧪 Model Training & Evaluation

### Models Used:
- **Logistic Regression**
- **Decision Tree Classifier**
- **Support Vector Machine (SVM)**

### Evaluation Metrics:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

### Results Summary:

**Logistic Regression:**
- Accuracy: 77.26%
- Precision: 72.93%
- Recall: 51.87%
- F1 Score: 60.62%

**Decision Tree Classifier:**
- Accuracy: 96.21%
- Precision: 95.60%
- Recall: 93.05%
- F1 Score: 94.31%

**Support Vector Machine (SVM):**
- Accuracy: 77.08%
- Precision: 72.73%
- Recall: 51.34%
- F1 Score: 60.19%

### Best Model: Decision Tree (after tuning)
- Accuracy: 94.58%
- Precision: 92.90%
- Recall: 90.91%
- F1 Score: 91.89%

---

📬 Contact
For questions, suggestions, or collaborations:
samveelkhan0313@gmail.com
