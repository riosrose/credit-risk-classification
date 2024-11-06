# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

## Results

# Logistic Regression Model Performance:
 - Precision:
 * For 0 (healthy loans): Precision is 1.00, meaning that 100% of the loans predicted as healthy (0) were actually healthy. This is a perfect score.
 * For 1 (high-risk loans): Precision is 0.84, meaning that 84% of the loans predicted as high-risk (1) were actually high-risk. While this is fairly high, there is still some room for improvement.
- Recall:
 * For 0 (healthy loans): Recall is 0.99, meaning that 99% of the actual healthy loans were correctly identified as healthy. This is an excellent recall score.
 * For 1 (high-risk loans): Recall is 0.94, meaning that 94% of the actual high-risk loans were correctly identified as high-risk. This is also a very good recall score, though slightly lower than for the healthy loans.
- F1-score:
 * For 0 (healthy loans): The F1-score is 1.00, indicating perfect balance between precision and recall for healthy loans.
 * For 1 (high-risk loans): The F1-score is 0.89, which indicates a good balance between precision and recall for high-risk loans, though slightly lower than the perfect score for healthy loans.
 
 - Overall Performance:
 * The accuracy of the model is 0.99 (99%), meaning the model correctly predicted 99% of the test data, which is excellent.
 * The macro average F1-score is 0.94, which indicates a good overall performance across both classes.
 * The weighted average F1-score is 0.99, reflecting the model’s strong performance, particularly due to the dominance of the healthy loans class.

- Conclusion:
 * The model performs exceptionally well for predicting healthy loans (0), with perfect precision and F1-score.
 * It also performs very well for predicting high-risk loans (1), with a precision of 0.84, recall of 0.94, and an F1-score of 0.89. This suggests that while the model is good at identifying high-risk loans, there is still a small percentage of misclassifications or false positives among them.
 * In summary, the logistic regression model is highly effective at predicting both classes, with strong performance for healthy loans and good performance for high-risk loans. The model is reliable, but there could still be some small improvements in predicting high-risk loans more accurately (e.g. improving precision slightly).