# MTN Customer Churn Prediction

# 🎯 Business Problem
MTN observed a decline in customer retention, resulting in revenue loss. The objective was to:

Predict the likelihood of churn for each customer.

Identify key drivers of churn.

Provide actionable insights for retention strategies.

# 2️⃣ Statistical Framing
Translated the business problem into a binary classification task (churn = 1, no churn = 0).

Conducted Chi-Square Tests for independence between categorical variables and churn.

Analyzed numeric feature distributions across churn classes.

Created new features to capture customer tenure, service usage, and contract types.

# 3️⃣ Modeling
Baseline Model: Logistic Regression for interpretability.

Advanced Models:

Random Forest Classifier

XGBoost Classifier

Validation:

Stratified K-Fold Cross-Validation

Evaluation metrics: Accuracy, Precision, Recall, F1 Score, ROC-AUC

# 4️⃣ Model Evaluation
Compared model performance:

Logistic Regression ROC-AUC: ~0.78

Random Forest ROC-AUC: ~0.83

XGBoost ROC-AUC: ~0.88 (best performance)

Plotted confusion matrices and ROC curves.

# 📊 Key Statistical Techniques
Logistic Regression

Chi-Square Test of Independence

Cross-Validation

ROC Curve Analysis

Feature Importance Analysis

XGBoost Gradient Boosting

# ✅ Outcomes and Business Impact
Top churn predictors identified:

Contract type (month-to-month contracts have higher churn risk)

Tenure (newer customers are more likely to churn)

Monthly charges (higher charges correlate with churn)

Developed a predictive model enabling MTN to:

Prioritize high-risk customers for targeted offers.

Improve retention campaigns and reduce churn-related losses.

# 🚀 Next Steps
Deploy the model as an API for real-time scoring.

Integrate predictions into CRM workflows.

Conduct A/B testing of retention interventions.

# 📂 Repository Contents
notebooks/: Exploratory Data Analysis and Modeling

data/: Cleaned dataset (anonymized sample)

scripts/: Model training and evaluation scripts

outputs/: Visualizations and performance metrics


## 🖼️ Example Visualizations
![agedist](https://github.com/user-attachments/assets/ce267e5b-2047-4704-8e9b-601c56c1bd50)
![satisfaction rate](https://github.com/user-attachments/assets/420d2ee5-18f3-44e2-a7b6-83c9278cb32f)
![tenure in months](https://github.com/user-attachments/assets/a5c4d1e7-d40e-41f9-a8d9-990cd48f58d9)
![age vs data usage](https://github.com/user-attachments/assets/d360dd0b-ea1a-44fe-918c-aa301cf1a3c2)
![age vs satisfaction rate](https://github.com/user-attachments/assets/a1bcd114-3fe0-4abc-8e26-1055686818fb)
![correlation heatmap](https://github.com/user-attachments/assets/fc5005a7-6705-4b23-b180-34937bc32447)




