# Overfitting_practice_Kaggle
Daily practice to control overfitting via  deep neural networks and logarithmic loss to maintain a score of <=.693 on the validation/test data.

https://www.kaggle.com/c/dont-overfit-ii/data is where the necessary datasets can be located. 

What am I predicting?
You are predicting the binary target associated with each row, without overfitting to the minimal set of training examples provided.
Files
train.csv - the training set. 250 rows.
test.csv - the test set. 19,750 rows.
sample_submission.csv - a sample submission file in the correct format
Columns
id- sample id
target- a binary target of mysterious origin.
0-299- continuous variables.

Submissions are evaluated using AUCROC between the predicted target and the actual target value.
Submission File
For each id in the test set, you must predict a probability for the target variable. The file should contain a header and have the following format:
