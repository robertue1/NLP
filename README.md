# NLP
NLP and Unsupervised Learning

Abstract

For this project, the main goal is to create a classification algorithm, capable of determining which clients of a financial institution are likely to close their account. With this information, the bank, could offer those clients a reduction on their monthly fees, or some others benefits to incentive them to keep them as users. To reach the goal, historic data from the bank is used, in order to develop a baseline predicting model. From there, I evaluated more complex models and solutions tailored to deal with the imbalanced present in the data. The end result will be an interpretable model and a black box model, capable of providing better results.

Design

To achieve the goal of the project, EDA was applied in a highly iterative way. After building of the base model, feature engineering was used in order to increase the complexity of the data and helping the evaluated models improve their performance. Finally, hyperparameter tuning was used to generate the final models.

Data

Data set contains 10.000 data points, for unique clients of the bank, including: Salary, balance, age, country of residency, number of products, if user has a credit card and a column indicating if the client has closed their account.

Algorithms

Data Acquisition: Data obtained from Kaggle. Data Exploration: Observation of the data and its characteristics, looking for missing or unexpected values. Data Cleaning: Done initially and almost throughout the entire process. Data Visualization: Studying the performance of the models via graphs.

Feature Engineering

Creating groups based on age.
Analyzing if people tend to be savers, based on their balance / salary ratio.
Combining dummies variables with the rest of the numerical variables.
Creating a feature to measure the ratio of tenure compared to the number of products they hold.
Models

Logistic regression, k-nearest neighbors, and random forest classifiers were used. Baseline model was a KNN, that performed better than the logistic regression, before doing any kind of feature engineering on the data.

Model Evaluation and Selection

For this project, after generating a more complex dataset, the logistic regression was used as the model to bring the interpretability into the picture, and helps us take some more informed decisions to improve the customer satisfaction.

A RF model, turned out to be better for profit maximization, and that is why was included as another alternative.

Final Random Forest scores:

Accuracy 0.87
F1 0.57
precision 0.77
recall 0.45
Final Logistic Regression scores:

Accuracy: 0.82
F1: 0.55
Precision: 0.53
Recall: 0.56
Tools

Numpy and Pandas for data manipulation
Scikit-learn for modeling
Matplotlib and Seaborn for plotting
Communication

Submitted PDF slides and 5 minutes presentation.
