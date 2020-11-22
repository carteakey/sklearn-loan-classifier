# Loan classification with sklearn
using sklearn module to create and evaluate various machine learning models. This is the final project of the Coursera's Machine Learning with Python course

### About dataset
This dataset is about past loans. The __Loan_train.csv__ data set includes details of 346 customers whose loan are already paid off or defaulted. It includes following fields:

| Field          | Description                                                                           |
|----------------|---------------------------------------------------------------------------------------|
| Loan_status    | Whether a loan is paid off on in collection                                           |
| Principal      | Basic principal loan amount at the                                                    |
| Terms          | Origination terms which can be weekly (7 days), biweekly, and monthly payoff schedule |
| Effective_date | When the loan got originated and took effects                                         |
| Due_date       | Since it’s one-time payoff schedule, each loan has one single due date                |
| Age            | Age of applicant                                                                      |
| Education      | Education of applicant                                                                |
| Gender         | The gender of applicant                                                               |

We use the training set to build an accurate model and then use the test set to report the accuracy of the model using the following algorithms: 
- K Nearest Neighbor(KNN)
- Decision Tree
- Support Vector Machine
- Logistic Regression

### Report : 

| Algorithm           | Jaccard  | F1-score | LogLoss  |
|---------------------|----------|----------|----------|
| KNN                 | 0.703704 | 0.686067 | NA       |
| Decision Tree       | 0.796296 | 0.780146 | NA       |
| SVM                 | 0.722222 | 0.621266 | NA       |
| Logistic Regression | 0.740741 | 0.630418 | 0.493198 | 


			
			
