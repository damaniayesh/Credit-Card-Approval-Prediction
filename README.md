# Credit-Card-Approval-Prediction
Banks receive a lot of applications for issuance of credit cards. Many of them rejected for many reasons, like high-loan balances, low-income levels, or too many inquiries on an individual’s credit report. Manually analyzing these applications is error-prone and a time-consuming process. This task can be automated with the power of machine learning. The project provides the credit card approval predictor using different machine learning algorithm , just like the real banks do.

<img src="https://isaiminis.com/wp-content/uploads/2021/10/How-to-get-your-first-credit-card-approval-in-easy-steps.jpg" alt="CreditCard_Image>

# Consider the data present in the Credit Card Approval dataset file.
Following is the attribute related information:

1. ID: Unique Id of the row
2. CODE_GENDER: Gender of the applicant. M is male and F is female.
3. FLAG_OWN_CAR: Is an applicant with a car. Y is Yes and N is NO.
4. FLAG_OWN_REALTY: Is an applicant with realty. Y is Yes and N is No.
5. CNT_CHILDREN: Count of children.
6. AMT_INCOME_TOTAL: the amount of the income.
7. NAME_INCOME_TYPE: The type of income (5 types in total).
8. NAME_EDUCATION_TYPE: The type of education (5 types in total).
9. NAME_FAMILY_STATUS: The type of family status (6 types in total).
10. DAYS_BIRTH: The number of the days from birth (Negative values).
11. DAYS_EMPLOYED: The number of the days from employed (Negative values). This column has error values.
12. FLAG_MOBIL: Is an applicant with a mobile. 1 is True and 0 is False.
13. FLAG_WORK_PHONE: Is an applicant with a work phone. 1 is True and 0 is False.
14. FLAG_PHONE: Is an applicant with a phone. 1 is True and 0 is False.
15. FLAG_EMAIL: Is an applicant with a email. 1 is True and 0 is False.
16. OCCUPATION_TYPE: The type of occupation (19 types in total). This column has missing values.
17. CNT_FAM_MEMBERS: The count of family members.

This is a csv file with credit record for a part of ID in application record. We can treat it a file to generate labels for modeling. For the applicants who have a record more than 59 past due, they should be rejected.

After reading the data, we have the following columns.

ID: Unique Id of the row in application record.
MONTHS_BALANCE: The number of months from record time.
STATUS: Credit status for this month.
X: No loan for the month
C: paid off that month
0: 1-29 days past due
1: 30-59 days past due
2: 60-89 days overdue
3: 90-119 days overdue
4: 120-149 days overdue
5: Overdue or bad debts, write-offs for more than 150 days.

# Problem Statement
To create a model that can predict whether an individual’s application for a credit card will be accepted or not.

# Conclusion
Performed various Machine Learning Algorithms among them KNN is performing well in terms of predicting my class 1, which is my class of importance where I want the model to be predict precisely in terms of rest of the class.
