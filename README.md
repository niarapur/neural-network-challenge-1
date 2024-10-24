# neural-network-challenge-1
Module 18 Challenge

# Background
Model is built for a company  to predict whether a borrower will repay their loan, it can provide a more accurate interest rate for the borrower. 

The business team has provided CSV file that contains information about previous student loan recipients. the target is to use neural networks to create a model that will predict the likelihood that an applicant will repay their student loans. The CSV file contains information about these students, such as : payment_history, location_parameter, stem_degree_score, gpa_ranking, alumni_success, study_major_code        time_to_completion, finance_workshop_score, cohort_ranking, total_loan_score, financial_aid_score

The output or Y value is the Credit Ranking that is determined.
# Model Details:

> A deep neural network with 2 layers activated by 'relu' was used
> A sequential model was deployed
> As the output layer is binary, a sigmoid function was used to activate it.
> The final model had the following accuracy statistics:
> Loss: 0.5125547647476196, Accuracy: 0.7549999952316284
> Model can be fuether optimized by addiing more data
> Model should be checked for inherent biases in contextual data 