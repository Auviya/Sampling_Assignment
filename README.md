# Sampling_Assignment
An overview of various sampling techniques that help us deal with with a highly imbalanced dataset and make accurate predictions in less amount of time

To accomplish this task we have taken a highly imbalanced dataset that after train-test-split contained only 8 examples of the minority class to deal with this we have used oversampling keeping in mind that undersampling in this situation 
will return a rather small population size that we would need to sample.

On oversampling we have about 1218 records out of which we have taken 384 sample size as derived by Cochran's Formula at a 95% confidence level and a 5% margin of error.
Also as our population has been treated for imbalance using oversampling the value of p parameter has accurately been taken as 0.5.

We have used 4 different sampling techniques enumerated as follows with is sample size:
1.Simple Random Sampling
2.Stratified Random Sampling
3.Clusted Sampling
4.Systemation Sampling

The 5th sample is derived using a 99% confidence level keeping the rest of the parameters to be same we have used SRS with this sample size

On these 5 samples we have applied 5 different models each as follows:
1.Logistic Regression
2.Decision Tree Classifier
3.Random Forest Classifier
4.SVM 
5.Neural Network Classifier

All these have been chosen keeping in mind he initial imbalance in data and also the fact that this is a binary classification problem.

On applying these models we got results as displayed in the png file in this repository that helps us to make the following conclusions
1. The Random Forest performs the best and SVM Classifier performs the worst across all samples 
2.Cluster Sampling Provided the best overall accuracy and SRS with 95% the worst 


