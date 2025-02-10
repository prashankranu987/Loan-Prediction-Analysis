**Loan Prediction Analysis**

This project aims to predict whether a loan will be approved or rejected based on various attributes of loan applicants. Using a dataset with features such as gender, income, credit history, and more, we build and evaluate machine learning models to predict the loan approval status.

**Dataset Overview**

The dataset used in this project contains information about 614 loan applicants and includes the following columns:

**Loan_ID**: Unique identifier for each loan.

**Gender**: Gender of the applicant (Male/Female).

**Married**: Marital status of the applicant (Married/Single/Other).

**Dependents**: Number of dependents the applicant has.

**Education**: Education level (Graduate/Under Graduate).

**Self_Employed**: Whether the applicant is self-employed (Y/N).

**ApplicantIncome**: Monthly income of the applicant.

**CoapplicantIncome**: Monthly income of the co-applicant.

**LoanAmount**: The loan amount applied for (in thousands).

**Loan_Amount_Term**: Loan term (in months).

**Credit_History**: Credit history of the applicant (1.0 = Good, 0.0 = Poor).

**Property_Area**: Type of property area (Urban/Semi Urban/Rural).

**Loan_Status**: The loan approval status (Y = Approved, N = Not Approved).

**Project Workflow**

**1.Data Preprocessing**:

->Handle missing values by using mean/median imputation or removing rows/columns.

->Convert categorical variables into numeric ones using techniques like one-hot encoding or label encoding.
->Normalize numerical features to ensure models perform well.

**2.Exploratory Data Analysis (EDA):**

->Analyze the distribution of different variables.

->Visualize relationships between features and loan approval status.

->Check for correlations and outliers in the data.

**3.Feature Engineering**:

->Create new features such as TotalIncome (sum of ApplicantIncome and CoapplicantIncome).

->Investigate how different features affect the loan approval status.

**4.Modeling**:

->Train multiple model, with Logistic Regression.

**5.Model Evaluation**:

->Evaluate model performance using accuracy, precision, recall, F1-score 

->Use cross-validation to ensure model robustness.

**Key Insights**

**Income**: Higher applicant income and coapplicant income are correlated with a higher likelihood of loan approval.

**Credit History**: A good credit history (value 1.0) is a strong indicator of loan approval.

**Property Area**: Applicants from urban areas tend to have higher approval rate
