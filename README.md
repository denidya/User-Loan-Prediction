# User Loan Prediction
this repository are for predicted User Loan Status wheather user Eligible or Not Eligible.


This project focuses on predicting loan approval status using a logistic regression model. The analysis involves data loading, comprehensive data wrangling including handling missing values and encoding categorical variables, and exploratory data analysis to understand feature distributions and correlations. A logistic regression model was trained and evaluated using key metrics such as F1-score and a classification report, achieving a high overall F1 score of 0.8943. Feature coefficients were analyzed to identify the most influential factors in loan approval decisions. The project demonstrates proficiency in building and evaluating classification models for real-world applications, providing actionable insights into the factors driving loan approval.

# About Dataset
- Loan_ID: A unique loan ID.
- Gender: Either male or female.
- Married: Weather Married(yes) or Not Marttied(No).
- Dependents: Number of persons depending on the client.
- Education: Applicant Education(Graduate or Undergraduate).
- Self_Employed: Self-employed (Yes/No).
- ApplicantIncome: Applicant income.
- CoapplicantIncome: Co-applicant income.
- LoanAmount: Loan amount in thousands.
- Loan_Amount_Term: Terms of the loan in months.
- Credit_History: Credit history meets guidelines.
- Property_Area: Applicants are living either Urban, Semi-Urban or Rural.
- Loan_Status: Loan approved (Y/N).

# Some Insight from Dataset
- Distribution from User Eligible and Not Eligible
<img width="1004" height="525" alt="newplot" src="https://github.com/user-attachments/assets/05a70fb4-ba5a-43aa-99a7-9478ea01c086" />

- Feature Correlation
<img width="890" height="632" alt="download" src="https://github.com/user-attachments/assets/d4fc410a-fe09-4784-90b9-0e5093c76cb2" />

- Coefficient Correlation
<img width="418" height="263" alt="Screenshot from 2025-08-01 10-21-48" src="https://github.com/user-attachments/assets/e3458257-5db9-4056-9d50-6aafc5552874" />

- Prediction Scoring
<img width="470" height="213" alt="Screenshot from 2025-08-01 10-24-45" src="https://github.com/user-attachments/assets/f822b714-5a72-4a2f-90a4-9270649218d2" />
