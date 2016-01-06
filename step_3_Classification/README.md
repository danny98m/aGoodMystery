# step 3: Classification (aGoodMystery)

The models are classification models to differentiate authorial 
writing style as implemented by Eder, Rybicki, and Kestemont’s (2016) ‘Stylometry with R’ (stylo) . 
Stylo in R offers a healthy suite of supervised 
classification procedures, including a range of multivariate distant metrics and techniques such as Delta, 
Support Vector Machine (SVM), Naïve Bayes, and Nearest Shrunken Centroid (NSC)). 

0. First a small test. Shuffle our "whole pot" of texts and apply Delta

1. We scripted stylo to test "A Dream" in N-trials using a random selection of files for training 
sets in each trial. At least one text from each author is also included in the test set for each trial.  
As we save the stylo output from each trial, a follow-up Python script,
parses the collected results to build confusion matrices for each author.

2. Controls. (a) shuffling author names (b) k-fold validation.

