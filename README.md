# Module-14
Module 14 Challenge Assignment
Using a New Machine Learning Classifier for Algorithmic Trading

Background
Choosing a machine learning model to use in a trading strategy is a matter of trial and error. In this way, you find a model that produces the desired outcomes with an acceptable level of performance.
In the machine learning section of the boot camp, you learned about some classification models, such as logistic regression, support vector machines (SVM), and neural networks. In this activity, you'll train a logistic regression model to make trading predictions, backtest the results, and then evaluate its performance compared to that of a SVM model.

Instructions:


Open the provided starter code. Inspect and run all the cells up to the “Add a New Machine Learning Model” section to review the data loading and preparation process, as well as the inclusion of a SVM model in a trading algorithm.


Import the LogisticRegression model from scikit-learn.

Rewind Recall that LogisticRegression models are used for binary classification problems.



Using the same training data that the SVM model used (X_train_scaled and y_train), fit the LogisticRegression model.


Use the trained model to predict the trading signals for the training data. Use the classification_report module to evaluate the model.


Backtest the LogisticRegression model to evaluate its performance.


Compare the performance of the logistic regression and SVM models using the classification reports generated with the testing data.  Did the logistic regression model perform better than SVM? Write down your conclusions to share with the class.



References
