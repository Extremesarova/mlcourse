# MLCourse assignments

* Assignment 3
  * [Understanding Decision Trees for regression](https://github.com/Extremesarova/mlcourse_ai_bonus_assignments/blob/main/assignment03/assignment03_decision_trees.ipynb) `Bonus`  
    * Intuition for building decision trees for regression problems - step by step
    * Introduction (and implementation) of criterion for maximization, impurity of the node, calculation of leaf value
    * Prediction heart diseases using decision tree (feature engineering, data splitting, validation, hyperparameter search, feature importance)
  * [Implementation of the decision tree algorithm](https://github.com/Extremesarova/mlcourse_ai_bonus_assignments/blob/main/assignment03/assignment03_optional_implement_decision_tree.ipynb) `Bonus`  
    * Implementation of the decision tree algorithm from scratch in scikit-learn style for classification and regression problems:
      * Leaf values calculation (mean, median, voting)
      * Criterion implementation (entropy, gini, variance, mad_median)
      * Building tree, predicting, predicting probability
      * Testing implementation on real tasks (hyperparameter search, etc.)
* Assignment 7
  * [Dimensionality reduction and clustering methods](https://github.com/Extremesarova/mlcourse_assignments/blob/main/assignment07/a7-demo-unsupervised-learning.ipynb)
    * Working with Samsung Human Activity Recognition dataset (6 clusters).
    * Scaling data
    * Applying PCA
    * Clustering with K-Means (choosing the best number of clusters)
    * Agglomerative clustering
    * Calculating the Adjusted Rand Index for two clustering algorithms
    * Solving this task using SVM with linear kernel
  * Principal Component Analysis and Clustering `Bonus`
* Assignment 8
  * [Stochastic gradient descent for classification and regression](https://github.com/Extremesarova/mlcourse_ai_bonus_assignments/blob/main/assignment08/assignment08_implement_sgd_regr_and_clf.ipynb) `Bonus`  
    * Implementation of linear regression (SGD) from scratch in scikit-learn style and testing it on height/weight dataset
    * Comparing from-scratch regression implementation with scikit-learn implementation 
    * Implementation of logistic regression (SGD) with $L_2$ regularization from scratch in scikit-learn style and testing it on breast cancer UCI dataset
    * Solving movie review classification task (IMDB) using logistic regression and its SGD variation
      * Feature engineering using `CountVectorizer`
      * Understanding advantages of `SGDClassifier`
