# Telco_Churn_Prediction

This project aims to predict potential customer churn in a telecommunications company using historical customer data. The model was built with a complete machine learning pipeline, including preprocessing, SMOTE for data balancing, and a tuned Decision Tree Classifier.

📂 File Structure

data_telo_customer_churn.csv
Raw dataset containing customer information (demographics, subscribed services, billing details, and churn status).

final_pipe.sav
Trained machine learning pipeline ready for direct prediction.

Telco_Churn_Prediction.ipynb
Jupyter Notebook containing data preprocessing, exploratory data analysis (EDA), SMOTE oversampling, pipeline creation, model training, and performance evaluation.

⚙️ Key Features
Data Preprocessing: Handles categorical and numerical data as well as missing values.

Oversampling: Uses SMOTE to handle class imbalance.

Pipeline: Combines preprocessing, balancing, and modeling into one workflow.

Final model: Tuned Decision Tree Classifier (log_loss, max_depth=3, min_samples_split=20, min_samples_leaf=4, class_weight='balanced') with 86% of Recall.

Evaluation: Recall.

📌 Notes
The saved model (final_pipe.sav) can be used directly for predictions on new data without retraining.
