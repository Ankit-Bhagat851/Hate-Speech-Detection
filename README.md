# Hate-Speech-Detection
We studied the theoretical concept of hate speech. Its definition, laws and classification. Second, we collected dataset form online platforms as labelled and unlabeled data. Third we preprocessed it and analysed the dataset. Fourth we implemented 10 machine learning  algorithms namely Logistic Regression, Decision Tree Classifier, Gradient Boosting Classifier, Random Forest Classifier, AdaBoost Classifier, XGB Classifier, Gaussian Naive Bayes, Multinomial Naive Bayes, Stochastic Gradient Descent Classifier, KNeighbour Classifier, Support Vector Machine. Finally, we extracted a dataset from twitter of nearly 50,000 tweets and then performed the above mentioned algorithms.

Result of 1 lakh labelled tweets

|Name|Accuracy BOW|Accuracy TF-IDF|
|---|---|---|
Logistic Regression|0.79|0.79|
Decision Tree Classifier|0.74|0.75
Gradient Boosting Classifier|0.76|0.76
Random Forest Classifier|0.80|0.80
Adaboost Classifier|0.76|0.76
XBG Classifier|0.76|0.76
Gaussian NB|0.70|0.73
Multinomial NB|0.72|0.74
SGD Classifier|0.78|0.78
K Neighbours Classifier|0.74|0.72

Result of 50,000 unlabelled tweets

|Name |Count of Hate speech BOW|Count of Not Hate speech BOW|Count of Hate speech TF-IDF|Count of Not Hate Speech TF-IDF|
|---|---|---|---|---|
Logistic Regression|40710|10408|41182|9936
Decision Tree Classifier|27677|23441|28408|22710
Gradient Boosting Classifier|50301|817|50211|907
Random Forest Classifier|31420|19698|32731|18387
Adaboost Classifier|48800|2318|48367|2751
XBG Classifier|50463|655|50299|819
Gaussian NB|19664|31454|25992|25126
Multinomial NB|34250|16868|37242|13876
SGD Classifier|48308|2810|46974|4144
K Neighbours Classifier|29411|21707|26241|24877

