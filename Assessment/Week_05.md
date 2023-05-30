# Portfolio assignment week 5

## 1. SVC

The Scikit-learn library provides different kernels for the Support Vector Classifier, e.g. `RBF` or `polynomial`.

Based on the examples [in the accompanying notebook](../Exercises/E_LR_SVM.ipynb), create your own `SVC` class and configure it with different kernels to see if you are able to have it correctly separate the moon-dataset. You can also use a `precomputed` kernel. In addition, there are several parameters you can tune to for better results. Make sure to go through [the documentation](https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html).

**Hint**:

- Plot the support vectors for understanding how it works.
- Give arguments why a certain kernel behaves a certain way.

## 2. Model Evaluation

Classification metrics are important for measuring the performance of your model. Scikit-learn provides several options such as the `classification_report` and `confusion_matrix` functions. Another helpful option is the `AUC ROC` and `precision-recall curve`. Try to understand what these metrics mean and give arguments why one metric would be more important then others.

For instance, if you have to predict whether a patient has cancer or not, the number of false negatives is probably more important than the number of false positives. This would be different if we were predicting whether a picture contains a cat or a dog – or not: it all depends on the context. Thus, it is important to understand when to use which metric.

For this exercise, you can use your own dataset if that is eligable for supervised classification. Otherwise, you can use the [breast cancer dataset](https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset) which you can find on assemblix2019 (`/data/datasets/DS3/`). Go through the data science pipeline as you've done before:

1. Try to understand the dataset globally.
2. Load the data.
3. Exploratory analysis
4. Preprocess data (skewness, normality, etc.)
5. Modeling (cross-validation and training)
6. **Evaluation**

Create and train several `LogisticRegression` and `SVM` models with different values for their hyperparameters. Make use of the model evaluation techniques that have been described during the plenary part to determine the best model for this dataset. Accompany you elaborations with a conclusion, in which you explicitely interpret these evaluation and describe why the different metrics you are using are important or not. Make sure you take the context of this dataset into account.
