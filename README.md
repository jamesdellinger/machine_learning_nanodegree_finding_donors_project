# Project: Finding Charity Donors
*Using supervised learning algorithms to identify individuals most likely to donate to a charity.*

<img src="https://github.com/jamesdellinger/machine_learning_nanodegree_finding_donors_project/blob/master/mlndlogo.png" height="140">

For Udacity's [Machine Learning Engineer](https://www.udacity.com/course/machine-learning-engineer-nanodegree--nd009t) Nanodegree.

Topic: Supervised Learning.

## Overview
* I explored various supervised learning classifiers and ensemble methods to create a model that does the best job of predicting whether an individual earns more than $50,000 per year.
* A charity organization would first reach out to these higher income individuals when soliciting donations.
* The dataset contains various demographic information, such as education level and marital status, collected in the 1994 U.S. census for 45,222 individuals. It can be found in the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Census+Income).
* Algorithms I explored include Gaussian Naive Bayes, Support Vector Machines, and AdaBoost Classifiers.

## Concepts
* Applying a series of transformations and preprocessing techniques such as log-normalization and min-max scaling to manipulate the data into a workable format for a learning algorithm.
* For this project, my classifier's precision will be more important than its recall or accuracy, so I use as a performance metric the [F-beta score](https://en.wikipedia.org/wiki/F1_score), which is built on the harmonic mean of precision and recall.
* Establishing a benchmark for a solution to a problem: I use the F-score of a classifier that naively predicts every individual earns more than $50,000.
* Understanding exactly when and where a particular supervised learning algorithm should be used and when one should be avoided, based on each model's strengths and weaknesses.
* How to effectively tune various algorithms' hyperparameters.
* Using K-Fold cross-validation to compare the performance of various models.
* Extracting feature importances from a trained model, and using other feature selection techniques such as SelectKBest.
* Investigating whether a candidate solution model is adequate for the problem.

## My Completed Project
* [ipython notebook](https://github.com/jamesdellinger/machine_learning_nanodegree_finding_donors_project/blob/master/finding_donors.ipynb) / [html version](http://htmlpreview.github.com/?https://github.com/jamesdellinger/machine_learning_nanodegree_finding_donors_project/blob/master/report.html) / [pdf version](https://github.com/jamesdellinger/machine_learning_nanodegree_finding_donors_project/blob/master/finding_donors.pdf)

## Project Grading and Evaluation
* [Project Review](https://github.com/jamesdellinger/machine_learning_nanodegree_finding_donors_project/blob/master/finding_donors_project_review.pdf)

* [Project Grading Rubric](https://github.com/jamesdellinger/machine_learning_nanodegree_finding_donors_project/blob/master/finding_donors_project_grading_rubric.pdf)

## Dependencies
* [requirements.txt](https://github.com/jamesdellinger/machine_learning_nanodegree_finding_donors_project/blob/master/requirements.txt)

* [Anaconda .yml file](https://github.com/jamesdellinger/machine_learning_nanodegree_finding_donors_project/blob/master/finding_donors_project.yml)
