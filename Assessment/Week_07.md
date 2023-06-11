# Portfolio assignment week 7

## 1. Bagging vs Boosting
The scikit-learn library provides several options for bagging and boosting. It is possible to create your own boosting model based on a base model. For instance, you can create a tree based bagging model. In addition, scikit-learn provides AdaBoost. For XGBoost it is best to use the xgboost library.

Based on the theory in the [accompanying notebook](../Exercises/E_BAGGING_BOOSTING.ipynb), create a bagging, boosting and dummy classifier. Test these classifiers on the [breast cancer dataset](https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset). Go through the data science pipeline as you've done before:

1. Try to understand the dataset globally.
2. Load the data.
3. Exploratory analysis
4. Preprocess data (skewness, normality, etc.)
5. Modeling (cross-validation and training)
6. Evaluation
7. Try to understand why some methods perform better than others. Try different configurations for your bagging and boosting models.

