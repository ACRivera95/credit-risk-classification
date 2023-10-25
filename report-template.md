# Module 12 Report Template
Machine learning model 1:

              precision    recall  f1-score   support
           0       1.00      0.99      1.00     18765
           1       0.85      0.91      0.88       619
    accuracy                           0.99     19384
   macro avg       0.92      0.95      0.94     19384
weighted avg       0.99      0.99      0.99     19384


Machine learning model 2:

              precision    recall  f1-score   support
           0       1.00      0.99      1.00     18765
           1       0.84      0.99      0.91       619
    accuracy                           0.99     19384
   macro avg       0.92      0.99      0.95     19384
weighted avg       0.99      0.99      0.99     19384


We can observe the following:

Both models achieve an impressive overall accuracy of 99%. When examining their performance on class 1, Model 1 has an 85% precision and 91% recall, while Model 2 has an 84% precision and 99% recall.

The choice between these models depends on the specific task requirements:

Model 2 is ideal if the priority is to detect the majority of true class 1 instances, even if it means accepting some false positives.
Model 1 is a better choice if a balance between minimizing false positives and capturing most true positives in class 1 is needed.
Consider the broader context and business objectives when making this decision. For tasks where false positives have significant consequences, like loan approvals, Model 1 with higher precision for class 1 is advisable.