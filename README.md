# Health Care Readmission Prediction

This project aims to predict whether a patient will be readmitted to the hospital based on various clinical and demographic features. Accurate prediction of readmissions can help hospitals improve care quality and reduce unnecessary costs.

---

## Project Objective

To build a machine learning model that predicts **patient readmission** using historical health care data, focusing on features like admission type, diagnosis, hospital stay duration, and treatment outcome.

---

## Dataset
- Contains features like:
  - Gender
  - Admission Date & Discharge Date
  - Diagnosis
  - Treatment Outcome
  - Length of Stay
  - Readmission Status (Target)

---

## Exploratory Data Analysis (EDA)

- Checked for missing values and data imbalance
- Converted date columns to datetime format
- Created a new feature: `Stay_Days` (discharge - admission)
- Visualized:
  - Stay duration distribution
  - Readmission rates
  - Relationship between features and target

---

##  Data Preprocessing

- Label Encoding for binary features (`Gender`, etc.)
- One-Hot Encoding for multi-category features (`Diagnosis`, `Treatment_Outcome`)
- Removed irrelevant or duplicate columns
- Normalized/Scaled for numerical columns

---

## Model Building

- Used **Logistic Regression** for initial modeling
- Train-Test Split (80-20)
- Evaluated using:
  - Accuracy
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1-score)

---
