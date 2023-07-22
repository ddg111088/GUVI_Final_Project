# GUVI_Final_Project
## Customer Conversion Prediction

### Problem Statement
You are working for a new-age insurance company and employ mutiple outreach plans to sell term insurance to your customers. Telephonic marketing campaigns still remain one of the most effective way to reach out to people however they incur a lot of cost. Hence, it is important to identify the customers that are most likely to convert beforehand so that they can be specifically targeted via call. We are given the historical marketing data of the insurance company and are required to build a ML model that will predict if a client will subscribe to the insurance. 


#### The following result was obtained using several ML algorithms along with undersampling and SMOTE techniques:--

Undersampling and SMOTE are two of the most common methods for balancing imbalanced data. Undersampling reduces the number of examples in the majority class, while SMOTE creates synthetic examples of the minority class. This can help to improve the performance of machine learning models on imbalanced datasets.

Here are some of the advantages of using undersampling and SMOTE to balance data:

.They can be effective in improving the performance of machine learning models on imbalanced datasets.
.They are relatively easy to implement.
.They can be used with a variety of machine learning algorithms.

I used the F1 score to evaluate the performance of my binary classification model. The F1 score is a measure of accuracy that takes into account both the false positive rate and the false negative rate. It is calculated as the harmonic mean of precision and recall.

The F1 score is calculated as follows:

F1 = 2 * (precision * recall) / (precision + recall)
The machine learning algorithm and its F1 score are as follows:

|Algorithm	                       |F1 score with undersampling	           |F1 score with SMOTE
|--|--|--|
|Logistic regression	              |0.5190930787589498	                     |0.5106796116504854
|K-Nearest Neighbors (KNN)	        |0.5052950075642966	                     |0.4970414201183432
|Decision tree	                    |0.5023491145645103	                     |0.4970414201183432
|XGBoost	                          |0.5723058028860915	                     |0.5808045165843332
|Random forest	                    |0.5502768872048964	                     |0.5676105631562203

Here are some conclusions that we can build with the scores you provided:

XGBoost had the highest F1 score with both undersampling and SMOTE. This suggests that XGBoost is the most effective algorithm for this problem.
Logistic regression had the lowest F1 score with both undersampling and SMOTE. This suggests that logistic regression is not the most effective algorithm for this problem.
The F1 scores with SMOTE were slightly higher than the F1 scores with undersampling. This suggests that SMOTE may be a slightly more effective method for balancing the data than undersampling.
The F1 scores for all algorithms were relatively low. This suggests that the data is highly imbalanced, and that it may be difficult to achieve high accuracy with any algorithm.
Overall, the results suggest that XGBoost is the most effective algorithm for this problem. However, the data is highly imbalanced, so it may be difficult to achieve high accuracy with any algorithm. Further experimentation with different algorithms and parameters may be necessary to improve the performance of the model.
