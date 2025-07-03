# Machine-Language
# Loan Approval Prediction using Machine Learning

## Project Objective
Build a machine learning model to predict whether a loan application will be approved based on applicant data.

## Dataset Description
The dataset contains various features related to loan applicants:
- Gender, Married, Dependents, Education, Self_Employed
- ApplicantIncome, CoapplicantIncome, LoanAmount
- Loan_Amount_Term, Credit_History, Property_Area
- Target: `Loan_Status` (Y/N)

##  Technologies Used
- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

##  Data Preprocessing
- Filled missing values in categorical and numerical features.
- Applied label encoding to categorical variables.
- Standardized numeric features for better model performance.

## Exploratory Data Analysis
- Plotted feature distributions and their relationships with the target.
- Observed that credit history and income were strongly correlated with loan approval.

##  Model Building
- **Logistic Regression** was used as the baseline classifier.
- Accuracy score and confusion matrix were used to evaluate performance.

##  Results
- The model performed well on the test set.
- Credit history, income, and marital status were among the top predictors.

##  Conclusion
This model can assist financial institutions in automating and speeding up loan approval decisions based on applicant information.

##  Future Enhancements
- Integrate models like Random Forest, XGBoost.
- Perform hyperparameter tuning and k-fold cross-validation.
- Deploy as a web application using Flask or Streamlit.
