# Comparison of Different Feature Selection Techniques 

The goal of this notebook is to explore and compare different feature selection techniques scikit-learn's diabetes dataset to identify the important features. This enables us to identify the features that may contribute the most to machine learning models and also reduce the dimensionality of the dataset to address potential overfitting concerns and also reduce computation and memory requirements. 

The models explored in this notebook are:
* Pearson correlation coefficient using r_regression from sklearn (univariate feature selection)
* Mutual information using mutual_info_regression from sklearn (univariate feature selection)
* Random forest feature importance using RandomForestRegressor from sklearn (multivariate feature selection)
* Recursive feature elimination using sklearn.feature.selection.RFE with a Support Vector Regressor SVR (multivariate feature selection)
