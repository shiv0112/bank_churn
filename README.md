# bank_churn
Predictive Modeling for Customer Churn

In this study, we aimed to predict the subscription to a term deposit by a customer of a Portuguese banking institution based on their response to direct marketing campaigns. The goal was to use machine learning algorithms such as logistic regression, gradient boosting classifier, and random forest classifier to make this prediction.

Methods

The first step in our analysis was to pre-process the data. This involved: 
handling missing values - there was no missing value in the data
separating numerical and categorical variables
encoding categorical variables. 
Balanced the dataset
The features were selected using ensemble method using a adaboost classifier.
The data was then split into a training set and a test set to evaluate the performance of the models.
 
Next, we trained and evaluated the performance of the three machine learning algorithms: logistic regression, gradient boosting classifier, and random forest classifier.

The logistic regression model was trained on the training data and used to predict the likelihood of a customer subscribing to a term deposit. The model was evaluated based on accuracy =  74.85% , precision= 75.86%, recall=73.00%, and F1-score=74.40%.

The gradient boosting classifier was trained on the training data and used to predict the likelihood of a customer subscribing to a term deposit. The model was evaluated based on accuracy=95.87%, precision=92.80%, recall=99.47%, and F1-score=96.02%.

The random forest classifier was trained on the training data and used to predict the likelihood of a customer subscribing to a term deposit. The model was evaluated based on accuracy=96.81%, precision=94.46%, recall=99.47%, and F1-score=96.90%.

Results

The results showed that the random forest classifier had the highest accuracy, precision, recall, and F1-score among the three models. The accuracy of the random forest classifier was 96.81%, precision was94.46%, recall was 99.47%, and F1-score was 96.90%.
