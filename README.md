# Credit Risk Analysis Report

# Overview of the Analysis

The goal of this analysis is to evaluate the credit risk of borrowers using historical lending data from a peer-to-peer lending platform. 

The data includes various features of borrowers and their loan statuses, where a status of 0 indicates a healthy loan and a status of 1 indicates a loan that is at high risk of defaulting.

The objective is to build a machine learning model using logistic regression to predict whether a loan will default based on the available features. 

This prediction will help the lending company make informed decisions about loan approvals.

# Results

•	Accuracy Score: 99%

	The logistic regression model achieved a high accuracy of 99%. This indicates that the model is able to make correct predictions for most of the loans.
 
•	Precision Score (for loan status = 1): 0.84

	Precision measures the proportion of predicted positive loan defaults (status = 1) that are actually correct. The model has a precision of 0.84, meaning that when it predicts a loan to be at high risk of defaulting, it is correct 84% of the time.
 
•	Recall Score (for loan status = 1): 0.94

	Recall measures how many of the actual high-risk loans (status = 1) the model successfully identified. The model's recall is 0.94, meaning it correctly identifies 94% of all high-risk loans.
 
# Summary

The logistic regression model demonstrates high performance in terms of both precision and recall. 

With an accuracy of 99%, the model is reliable and provides accurate predictions for most loans. 

The precision score of 0.84 indicates that the model is relatively good at identifying high risk loans when it predicts a loan will default. 

However, the model's recall score of 0.94 is particularly noteworthy, as it captures a significant portion of the actual high-risk loans, which is crucial for mitigating financial risk.

While the model performs well, there is room for improvement in precision. 

This means the model may flag healthy loans as high-risk, leading to unnecessary rejections or further scrutiny of some loans. 

The company may want to fine-tune the model further by exploring other machine learning algorithms, such as decision trees, random forests, or boosting methods, to potentially enhance precision without sacrificing recall.

# Recommendation

Given the model's high accuracy, recall, and reasonable precision, I recommend using this logistic regression model as a first step for credit risk classification. 

However, further exploration of more complex models could be beneficial to improve its performance

# Further Analysis

I tested two algorithms to evaluate if they could improve prediction results on the dataset:

Random Forest

Voting Classifier

# Conclusion

The Voting Classifier yielded better predictions, particularly for high-risk loans, and is therefore recommended for use with this dataset. 

It demonstrates improved performance in identifying high-risk loans, making it a more reliable option for credit risk classification.
