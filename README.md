# Feature-Selection-Dimensionality-Breast-Cancer
How to select features and why, and reduce dimensionality of the data set in order to optimise the model better.


In this notebook, we will explore various feature selection and dimensionality reduction techniques in reference to the Wisconsin breast cancer dataset on Kaggle. This dataset contains 569 breast cancer observations in which 357 of them are benign and 212 of them are malignant. The goal is to train a machine learning model that is able to classify a random breast cancer observation as either benign or malignant. I have chosen the random forest classifier for this particular problem.

The techniques that will be covered in this notebook as follows:

* Variance inflation factor (VIF)
* Univariate feature selection
* Recursive feature elimination
* Model-based feature selection
* Principal component analysis (PCA)


We will compare the effectiveness of each technique by examining the accuracy of our model at making predictions. More specifically, we will be using the confusion matrix, which is a common approach to test the performance of a model in binary classification using Random Forest classifier
