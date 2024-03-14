This repository provides a synthetic dataset of 1500 examples designed for binary classification tasks.

Class 1 is formed using three Gaussian distributions, each having means [6,14], [10,6], and [14,14], whereas Class 0 is derived using a uniform distribution with a range of [0, 20].

The primary goal is to demonstrate the use of a Decision Tree classifier in appropriately classifying cases.

This code illustrates how to create synthetic data, train a Decision Tree classifier, visualise the decision tree, and assess model performance at various depths.

It offers an organised approach to studying and analysing classification tasks with Decision Trees.

Python's NumPy and Matplotlib packages are used to generate datasets.

The scikit-learn library is used to implement the Decision Tree classifier. 

The classifier is trained on the training set once the dataset is divided into testing and training sets.

The classifier's accuracy is then evaluated using the test set.
