# Loan approval prediction
The main objective of this project is to automate the loan qualifying procedure. Predict loan approval is a decision-making process for determining whether an applicant is eligible for a loan or not, based on applicant information.

# Introduction
With the enhancement in the banking sector lots of people are applying for bank loans but
the bank has its limited assets which it has to grant to limited people only, so finding out to
whom the loan can be granted will be a safer option for the bank. In order to automate the
loan qualifying procedure we implemented a machine learning algorithm in order to predict
the loan approval.

# Models
The problem is a binary classification and different machine learning models were used: 

● Logistic Regression

● Support Vector Classification (SVC)

● Gaussian Naive Bayes (GaussianNB)

● K-Nearest Neighbors (KNeighborsClassifier)

● Linear Discriminant Analysis (LinearDiscriminantAnalysis)

# Benchmark
![immagine](https://user-images.githubusercontent.com/66021430/220392229-be2275d9-18f7-425d-84f6-1b2eb4d965bb.png)


# Conclusion
By taking into account the facts that we chose Precision as the main metric,
that these models do not perform well on unbalanced data and that our dataset is
unbalanced the models SVC and KNN are not the right models for the problem.

The focus was on the AUC score metric because is better to find a model which performs well in both minority and majority class and not just only in majority class.

The best model would be Logistic Regression since it got a high precision, recall, f1-score for each class and the most important metric, in an unbalanced dataset, the highest AUC score.

The problem is a binary classification problem. The goal is to correctly classify people who should not get approved for a loan. That's the reason the main focus is the F1-score and the AUC score
score.

