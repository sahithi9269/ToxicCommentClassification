# ToxicCommentClassification
This project uses machine learning to categorize harmful statements in online debates. The occurrence of harmful comments has increased as more people use online
communication platforms. Comments that are hurtful, abusive, or disrespectful to others are considered toxic. This project's goal is to create a machine learning model
that can distinguish between hazardous and non-toxic comments in online discussions. We make use of a dataset of comments that have been flagged as poisonous from the
Wikipedia Talk page. Using a variety of methods, including Naive Bayes, Logistic Regression, and Support Vector Machines, the machine learning model is trained on this
dataset. Precision, recall, and F1-score metrics are used to assess the model's performance.With an F1-score of 0.90, the results demonstrate that the Support Vector
Machines method performs the best. This project offers a mechanism to automatically flag poisonous comments, enabling for more effective and efficient monitoring of
online debates. This technology has significant implications for online content moderation.

There are labels for each of these six categories of toxicity for each comment in the dataset. The dataset includes the following attributes for each comment in 
addition to the text of the comment and the labels indicating its toxicity:
1. id, a special code that identifies each remark
2. comment text - the comment's text
3. toxic - a flag that indicates whether the statement is harmful.
4. severe toxic, a binary label that designates whether the comment is extremely toxic.
5. "obscene" is a binary label that denotes whether the comment is vulgar.
Threatening is a binary label that indicates whether a comment is threatening or not.
7. insult - a binary designation of whether the remark is insulting
8. The binary label identity hate indicates whether a comment contains identity hate.
Each training set and testing set in the dataset contains the identical properties for each comment. Almost 143,000 comments are present in the training set,
while over 15,000 comments are present in the testing set.
RESULT EVALUATION:
Here are some typical outcomes for this dataset using different categorization algorithms documented in the literature to give you a general idea of what performance
 metrics you might expect:
Logistic Regression: Recall is 0.71, F1 is 0.73, Precision is 0.76 and accuracy is 0.95.
Precision, Recall, F1, and Accuracy for Support Vector Machines (SVM) are each 0.77, 0.69, 0.73 and 0.95.
Random Forest: Recall=0.48, Precision=0.67, Accuracy=0.94, F1=0.56
XGBoost: Recall=0.68, Precision=0.76, Accuracy=0.95 , F1=0.71
It is crucial to keep in mind that the performance metrics can differ significantly depending on the precise methods employed for feature engineering,
text pre-processing, and hyperparameter tuning, among other things. As a result, it is advised to try out several algorithms and strategies to see which ones work
 well together for your particular project.




