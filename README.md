
🌲 Loan Approval Prediction
This project predicts loan approval status using applicant and loan-related features from the Loan Approval Dataset. The task is framed as a binary classification problem (Approved/Rejected).

📌 Project Overview
Data loading and initial exploration

Handling categorical features using Label Encoding

Addressing class imbalance through class weighting

Splitting data into training and testing sets

Training multiple classification models including:

Random Forest

Gradient Boosting

Logistic Regression

Support Vector Machine
Evaluating model performance using classification reports, confusion matrices, and ROC-AUC scores

Visualizing class distribution and feature importance

⚙️ Tech Stack
Python (Pandas, NumPy, Matplotlib, Seaborn)

Scikit-learn (train_test_split, classification models, metrics, LabelEncoder, StandardScaler)

Imbalanced-learn (SMOTE, RandomUnderSampler)

Jupyter Notebook

📊 Dataset Features
The dataset contains 13 features including:

Applicant information (income, dependents, education, employment status)

Loan details (amount, term)

Credit score (cibil_score)
Asset values (residential, commercial, luxury, bank)

Target variable: loan_status (Approved/Rejected)

🔍 Key Insights
The dataset shows significant class imbalance with Approved loans being approximately 1.6 times more frequent than Rejected loans

Random Forest classifier achieved excellent performance with:

98% overall accuracy

97% precision and 95% recall for Rejected class

99% ROC-AUC score

Feature importance analysis revealed key predictors for loan approval decisions
