# Handwritten Hangul OCR (Optical Character Recognition)

Hangul is the writing system of the Korean language. Hangul is made up of 10 consonants and 14 vowels, making it an alphabet with a total of 24 letters.

This project takes an image of a korean character as an input and classifies it using SVM classifier.

The following steps are followed in the project:

1. Generating Hangul image dataset using free Hangul-supported fonts found online.
2. Analyzing and preparing the data.
3. Splitting the dataset into train and test data.
4. Performing feature scaling by dividing all the features by the maximum value.
5. Training the model using SVM classifier.
6. Predicting labels on test data.
7. Evaluating the model based on accuracy metric.
8. Testing model on real data.
9. Printing the confusion matrix.

### Support Vector Machine (SVM)

Support vector machines (SVMs) are a set of supervised learning methods used for classification, regression and outliers detection.

The advantages of support vector machines are:

1. Effective in high dimensional spaces.
2. Effective in cases where number of dimensions is greater than the number of samples.
3. Uses a subset of training points in the decision function (called support vectors), so it is also memory efficient.
