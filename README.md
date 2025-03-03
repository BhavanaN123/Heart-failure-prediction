
# Heart Failure Prediction Using Machine Learning: Feature Selection & Hyperparameter Optimization
# Objective
This research aims to improve heart failure prediction accuracy by optimizing hyperparameters and selecting the most relevant features.
The primary goal of this research is to enhance the accuracy and efficiency of heart failure prediction models by leveraging hyperparameter optimization and feature selection techniques.

Heart failure is a critical health condition that requires early and accurate diagnosis to improve patient outcomes. Traditional predictive models often suffer from limitations such as high dimensionality, suboptimal hyperparameters, and redundant features, which can negatively impact performance.

To address these challenges, this study aims to:

✅ Compare multiple supervised learning algorithms to identify the best-performing model.

✅ Apply feature selection techniques to identify the most influential factors in heart failure prediction.

✅ Optimize hyperparameters using Grid Search and Random Search to enhance model performance.

✅ Improve model efficiency by reducing the number of features while maintaining high predictive accuracy.

✅ Provide insights for clinical decision-making, helping healthcare professionals in early diagnosis and risk assessment.

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

