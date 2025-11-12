# Big-Data-Exam
## Context
This is a mock dataset to demonstrate visualization
## Data summary
- Rows: 6,362,620  
- Columns: 10  

## Data dictionary
- step — unit of time: 1 step = 1 hour.
- type — transaction type: CASH-IN, CASH-OUT, DEBIT, PAYMENT, TRANSFER.
- amount — transaction amount (local currency).
- nameOrig — originator account ID.
- oldbalanceOrg — originator balance before the transaction.
- newbalanceOrig — originator balance after the transaction.
- nameDest — recipient account ID.
- oldbalanceDest — recipient balance before the transaction. (No info for merchant IDs starting with "M".)
- newbalanceDest — recipient balance after the transaction. (No info for merchant IDs starting with "M".)
- isFraud — label: fraudulent transaction (true/false).
- isFlaggedFraud — flagged when single transfer > 200,000.

## Data source
https://www.kaggle.com/datasets/chitwanmanchanda/fraudulent-transactions-data?resource=download

