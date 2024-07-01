# credit-risk-classification

## Overview of the Analysis
#The purpose of this lending data analysis is to understand how well the model is making predictions.
#Are loans getting labeled as healthy or high risk appropriately? Using LogisticRegression to predict, we investigate this quesiton.



## Results
#For all of the loans predicted as healthy(0), the precision was 1.00, 100% were healthy!
#For the high risk loans, out of all predicted to be high risk, unfortunately only 83% were actually high risk
#aka 1. 



#Accuracy Score
#Accuracy tells us how many times something was predicted correctly overall.
#Out of this models predictions we achieved 99% accuracy.

#Precision Score
#Precision shows us how many times the model got it right, and the times it got it wrong,
#showing an overall picture of true positives and negatives, and false positives and negatives.
#Here healthy loans were predicted correctly 100% of the time, and high risk loans were predicted correctly only 83% of the time.

#Recall Score
#Recall focuses on positives, telling us how many correctly predicted positives or yes's do we have
#compared with how many there actually are. For our healthy loan predictions, we have 99% recall,
#however for high risk(1), only 92% of our positives were predicted, meaning there were more healthy loan positives that were not predicted this way.


## Summary
#Although the accuracy of this model is confident, I have concerns over the precision.
#To me this feels to be an unfortunate outcome, as people who actually qualify for a loan
#and would satisfy the algorithim for a healthy loan, would get automatically deflected
#if a human were not to review this work. I would much rather the opposite numbers,
#with the healthy being overshot, and high risk being accurate.
#For these reasons I would not currently recommend this model for use by the company,
#unless there is human oversight.
