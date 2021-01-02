# Practical-Machine-Learning-Course-Project

This report is for the final course project for the Practical Machine Learning course, part of the John Hopkins Statistics and Machine Learning Specialization on Coursera.

The goal of the project is to analyze data captured by a third party and build an algorithm to predict how correctly the exercise was performed.
The model will be used to predict a test set of 20 records.

The training and test data for this was provided at the following location: http://web.archive.org/web/20161224072740/http:/groupware.les.inf.puc-rio.br/har
 
The "correctness" of the exercise is denoted by the "classe" variable in the data and uses a code A-E. That is what we will predict.

##Conclusion

My final Model was trained using Random Forests.

I was able to train the model to an accuracy of 99.71% on my Validation set.
The estimated Out of Sample error is .29%

The predictions for the Test set are as follows:

  [1] B A B A A E D B A A B C B A E E A B B B
