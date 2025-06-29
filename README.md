# 🏠 Home Loan Prediction Project
🔍 Project Overview
This project aims to predict the eligibility of applicants for a home loan using supervised machine learning techniques. It is based on data from Dream Housing Finance, a company that offers loans across rural and urban sectors in India.

The goal is to automate the loan approval process using customer details from an online application form — including information like gender, marital status, income, education, credit history, etc.

# 📌 Business Objective
The finance company seeks to:

Automate loan eligibility checks using machine learning.

Speed up the loan processing and reduce human dependency.

Target eligible customers with real-time decisions.

# 🧹 Data Preprocessing
Several preprocessing steps were carried out:

Merged ApplicantIncome + CoapplicantIncome into a single feature called Income.

Dropped irrelevant columns like Loan_ID.

Categorical encoding for variables like Gender, Married, Education, etc.

Handled missing values appropriately.

Checked for skewness in numerical features and applied transformations where needed

# 🛠️ Model Building & Selection
Multiple models were explored and evaluated:

Logistic Regression

K-Nearest Neighbours

Support Vector Classifier

Decision Tree Classifier

Random Forest Classifier

Gradient Boosting Classifier

Xtreme Gradient Boosting Classifier

For each model:

Hyperparameter tuning using GridSearchCV

Selected best features based on feature importance

Trained and tested on an 80-20 split

✅ Final Model: Decision Tree
🎯 Train Accuracy: 81.08%
🎯 Test Accuracy: 83.01%
📉 Cross-validation Score: 81.09%
✅ Saved using joblib as loan.joblib

# 🔮 Prediction on New Data
A prediction pipeline was created to process and predict new loan applications in real time.
The model returns:

1 — Loan Approved

0 — Loan Rejected

# 📊 Features Used
Some of the most influential features:

Education

LoanAmount

Loan_Amount_Term

Credit_History

Property_Area

Income

# 🧠 Tech Stack
Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)

Data Preprocessing, Data Wrangling, Feature Selection, Feature Engineering, 

Jupyter Notebook

Joblib (for model serialization)

# 🙌 Author
Behara Pavan Kumar



