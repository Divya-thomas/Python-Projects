# Python-Projects
 Comparing the metrics of different Scikit-Learn models

This notebook compares 3 different models on a small dataset.

A baseline RandomForestClassifier (all default parameters)
A RandomForestClassifier tuned with RandomizedSearchCV (and refit=True)
A RandomForestClassifier tuned with GridSearchCV (and refit=True)

The most important part is they all use the same data splits created using train_test_split() and np.random.seed(42).
