# Default Prediction - Credit Scoring
## Data
- Data source: Kaggle
- Data description: The data set HMEQ reports characteristics and delinquency information for 5,960 home equity loans. A home equity loan is a loan where the obligor uses the equity of his or her home as the underlying collateral
  
| Column Name                | Description                                                                                   |
|----------------------------|-----------------------------------------------------------------------------------------------|
| BAD                        | 1 = applicant defaulted on loan or seriously delinquent; 0 = applicant paid loan             |
| LOAN                       | Amount of the loan request                                                                   |
| MORTDUE                    | Amount due on existing mortgage                                                              |
| VALUE                      | Value of current property                                                                    |
| REASON                     | DebtCon = debt consolidation; HomeImp = home improvement                                     |
| JOB                        | Occupational categories                                                                      |
| YOJ                        | Years at present job                                                                         |
| DEROG                      | Number of major derogatory reports                                                           |
| DELINQ                     | Number of delinquent credit lines                                                            |
| CLAGE                      | Age of oldest credit line in months                                                          |
| NINQ                       | Number of recent credit inquiries                                                            |
| CLNO                       | Number of credit lines                                                                       |
| DEBTINC                    | Debt-to-income ratio                                                                         |

## Purpose
1. Compare the prediction performance of classification models based on evaluation criteria
2. Calculate the credit scores for each feature based on the Logit model 
