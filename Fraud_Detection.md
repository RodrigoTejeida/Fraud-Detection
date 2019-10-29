
*Objective:*
- Design a system capable of automatically catching fraudulent transactions.

*Data:*
- 182 MB of records, just over 6 million records with 11 columns
- Each record is a single transaction, marked as cash in, cash out, debit, credit, or transfer. Each transaction will also have the amount, the name of origin.
- There are 2 target columns. One appears to be an indicator isFraud, which should be a manual label. Another is a flag based on a rule applied, that is, when a transaction has been attempted for over 200,000.

*End Goal:*
- Find the right model, or combinations of models, that detect the most fraudulent transactions.