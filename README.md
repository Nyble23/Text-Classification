# Text-Classification

Apart from manual classification, another approach to text classification is machine-learning based classification. This type of classificatin is a supervised learning because the set of labeled data serves as training data for the machine. This means that manual classification can't be completed eliminated. We need some annotated data in order to train our machine.

Here, for text classification, [20 newsgroups](https://archive.ics.uci.edu/ml/datasets/Twenty+Newsgroups) dataset is used. This dataset has 20 classes, but I have demonstrated using only 5 classes.

There are many methods for text classification. Of those, only **multinomial Naive Bayes** and **K-Nearest Neighbour** are used here.

### Feature Selection

Feature selection is the process of selecting a subset of the terms ocuuring in the training set and the =n use only ths subset of features for text classification. Here, **TF-IDF** based feature selection and **Mutual Information** are used. The two feature-selection techniques are applied to both the classifiers.
