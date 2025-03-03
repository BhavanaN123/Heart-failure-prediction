
# Heart Failure Prediction Using Machine Learning: Feature Selection & Hyperparameter Optimization
# Objective
This research aims to improve heart failure prediction accuracy by optimizing hyperparameters and selecting the most relevant features.
The primary goal of this research is to enhance the accuracy and efficiency of heart failure prediction models by leveraging hyperparameter optimization and feature selection techniques.

Heart failure is a critical health condition that requires early and accurate diagnosis to improve patient outcomes. The Heart Failure Clinical Records Dataset is a collection of medical records from 299 patients who experienced heart failure. This dataset is often used to predict patient mortality due to heart failure.

# Dataset Overview:

  **Number of Instances**: 299 patients

  **Number of Features**: 12 clinical features

**Features**:

**Age**: Age of the patient (years)

**Anaemia**: Decrease of red blood cells or hemoglobin (boolean)

**Creatinine Phosphokinase (CPK)**: Level of the CPK enzyme in the blood (mcg/L)

**Diabetes**: Whether the patient has diabetes (boolean)

**Ejection Fraction**: Percentage of blood leaving the heart at each contraction (%)

**High Blood Pressure**: If the patient has hypertension (boolean)

**Platelets**: Platelet count in the blood (kiloplatelets/mL)

**Serum Creatinine**: Level of serum creatinine in the blood (mg/dL)

**Serum Sodium**: Level of serum sodium in the blood (mEq/L)

**Sex**: Gender of the patient (Male/Female)

**Smoking**: Whether the patient smokes (boolean)

**Time**: Follow-up period (days)

**Target Variable:**

**DEATH_EVENT**: Indicates if the patient died during the follow-up period (boolean)

# Algorithms Analyzed
Eight supervised learning classification models were evaluated:

✅ Logistic Regression

✅ K-Nearest Neighbors (KNN)

✅ Naive Bayes

✅ Support Vector Machine (SVM)

✅ Decision Tree

✅ Random Forest

✅ LightGBM

✅ XGBoost

# Feature Selection
Feature selection techniques were applied to determine the most critical attributes for heart failure prediction. The top 5 most significant features were identified based on importance scores.

# Hyperparameter Optimization
To enhance model performance, Grid Search and Random Search methods were used for tuning hyperparameters.

# Results & Key Findings
Algorithm	Features Used	Accuracy (%)
Random Forest	All 12 Features	87.83
KNN	Top 5 Features	87.83
🔹 Random Forest performed best using all 12 features.
🔹 KNN achieved the same accuracy with only top 5 selected features.

# Conclusion
This study demonstrates the effectiveness of feature selection and hyperparameter tuning in improving heart failure prediction models. The findings suggest that KNN with top 5 features can achieve the same accuracy as Random Forest with all features, potentially reducing model complexity without compromising performance.

