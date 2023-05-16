# Module 12 Report 

## Overview of the Analysis

The purpose of this analysis was to evaluate the performance of machine learning models to evaluate Credit Loan risks. The data used in this analysis pertained to the borrower's financial information such as borrower income, loan size, number of open accounts, and a few others. The goal was to predict the creditworthiness of borrowers based on the models precision, recall, and f1-scores.

The variables being predicted in the models were:

- Class Green and Class Yellow (binary classification)

Throughout the analysis, the following stages of the machine learning process were followed:

1. Data preprocessing and exploration. In this stage, the raw data was preprocessed to ensure its quality and suitability for analysis. This involved handling missing values, removing outliers, and transforming variables if necessary.

2. Feature selection and engineering. Feature selection techniques were used to identify the most relevant and informative features for predicting credit loan risks.

3. Model training and evaluation. Multiple machine learning models were trained using the preprocessed data. Evaluation metrics such as accuracy, precision, recall, and F1-score were calculated to assess the models' performance.

4. Performance assessment and comparison. The performance of the trained models was assessed using the evaluation metrics mentioned above. The models were compared based on their ability to accurately predict credit loan risks.

Two machine learning models were employed using logistic regression. For the second model, to prevent the models from being biased towards the majority class, resampling methods were used to address class imbalance in the datasets.

## Results

The results of the machine learning models are as follows:

- Machine Learning Model 1:
  - Precision: 1.00 (Class Green), 0.87 (Class Yellow)
  - Recall: 1.00 (Class Green), 0.89 (Class Yellow)
  - F1-score: 1.00 (Class Green), 0.88 (Class Yellow)

- Machine Learning Model 2:
    - Precision: 1.00 (Class Green), 0.87 (Class Yellow)
- Recall: 1.00 (Class Green), 1.00 (Class Yellow)
  - F1-score: 1.00 (Class Green), 0.93 (Class Yellow)

## Summary

Based on these results, both models perform well in predicting credit loan risks, with high precision, recall, and F1-scores. Model 2 shows better performance in predicting Class Yellow, as indicated by the higher F1-score compared to Model 1.

The choice of the model to use depends on the specific problem at hand. If predicting Class Yellow (higher credit risks) is of utmost importance, Model 2 is recommended due to its higher F1-score in that class. However, if the focus is more balanced between the two classes, both models can be considered as they exhibit high precision, recall, and F1-scores for both classes.

It is crucial to consider the problem's context and the relative importance of correctly predicting each class. For instance, if avoiding false negatives (missing high credit risks) is a priority, a model with higher recall in Class Yellow would be preferred. Alternatively, if minimizing false positives (false alarms) is more critical, a model with higher precision in Class Yellow would be preferred.

Overall, the analysis provides valuable insights into the performance of the machine learning models and offers a recommendation based on the problem's specific requirements and priorities.



