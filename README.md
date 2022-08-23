# ods_credit_scoring
[Сredit scoring competition](https://ods.ai/competitions/dl-fintech-bki) based on credit history data from the Alfa-Bank Machine Learning Laboratory and the Open Data Science Community.

## DATA

Credits for the training sample are taken over a period of M months, and credits for the test sample are taken over the next K months.

Whole train set shape: 3000000, 450;

Whole test set shape: 500000, 450.

The **target variable** is a binary value that takes the values 0 and 1, where 1 corresponds to the client's default on the loan.

## Metrics
Competition metric is **ROC AUC**.

Public leaderboard: 0.751802;

Private leaderboard: 0.748337.
