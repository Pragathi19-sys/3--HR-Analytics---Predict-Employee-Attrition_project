# HR Analytics – Employee Attrition Prediction & Decision Support

Domain: Human Resources Analytics & Machine Learning

## 1. Introduction
Employee attrition is an important HR challenge because frequent resignations increase recruitment costs, training requirements, workload for existing staff, and loss of organizational knowledge. This project develops an HR analytics solution that studies historical employee data to identify patterns associated with attrition and estimate the risk of future attrition.

## 2. Abstract
Analyzes employee attributes such as department, job role, income, overtime, satisfaction, tenure, and promotion history. Workflow includes preprocessing, EDA, classification models, SHAP explainability, and Power BI dashboard. System is a decision-support tool; predictions indicate risk based on historical patterns.

## 3. Tools Used
- Python - Data analysis and machine learning
- Pandas, NumPy - Data loading, cleaning and transformation
- Matplotlib, Seaborn - EDA and visualization
- Scikit-learn - Classification models and evaluation
- SHAP - Explainable AI and prediction interpretation
- Power BI - Interactive HR analytics dashboard
- Joblib - Saving the trained model

## 4. Steps Involved
- Dataset Selection: HR employee attrition dataset with demographic, job, compensation, satisfaction, overtime, tenure attributes
- Data Preprocessing: Checked missing values and duplicates, removed IDs, encoded categoricals, Attrition to binary (1 = left, 0 = stayed)
- Exploratory Data Analysis: Attrition across departments, job roles, overtime, income, age, job satisfaction, years at company, promotion history
- Model Development: Logistic Regression, Decision Tree, Random Forest with 80:20 stratified train-test split
- Model Evaluation: Accuracy, Precision, Recall, F1-score, ROC-AUC, Confusion Matrix, ROC curve
- Explainable AI: SHAP on Random Forest for global and individual predictions
- Power BI Dashboard: Workforce metrics, attrition patterns, risk levels, employee-level info
- Reporting: Documented findings with practical attrition prevention suggestions

## 5. Conclusion
Transforms HR data into end-to-end analytics solution. EDA shows historical patterns, ML estimates risk systematically, SHAP makes it interpretable, Power BI makes it HR-friendly.

## 6. Limitations & Future Work
- Predictions are risk scores, not guarantees
- Future: Larger dataset, calibrated probabilities, model monitoring, secure HR app deployment
