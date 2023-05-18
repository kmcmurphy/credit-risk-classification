Credit Risk Classification

This project uses a supervised machine learning model to categorize the creditworthiness of borrowers by spliting them into low and high risk groups. It first uses logistical regression with the standard data and then logistical regression with resampled data, based on the imbalance of borrower types.

The results:
When running the model using only the test data:
- Accuracy: The f1 score reported 99% 
- Precision: The precision for healthy loans was 100% while high-risk loans came in at 87%
- Recall: The precision for healthy loans was 100% while high-risk loans came in at 89%


When running the model using resampled test data:
- Accuracy: The f1 score reported 100% 
- Precision: The precision for healthy loans was 100% while high-risk loans remained at 87%
- Recall: The precision for healthy loans was 100% while high-risk loans increased to 100%


Overall, both models scored very highly, with the resampled data reporting nearly no false nagatives and fewer false positives than the standard model.

