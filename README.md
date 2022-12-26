# Comparing Classifiers
**A comparison of gradient boosting and k-nearest neighbors classification models**
### Overview
Using biomedical data from the University of California, Irvine Machine Learning Repository, I compared the ability of gradient boosting and k-nearest neighbor models to accurately predict if a patient has Parkinson's Disease given 22 unique features. This process entailed:
- Isolating the features and values to be used from the original data
- Scaling the features using the `sklearn.preprocessing` package
- Splitting the features and values into training and testing sets with the `sklearn.model_selection` package (75% training, 25% testing)
- Fitting a gradient boosting model with `XGBClassifier` from `xgboost`
- Writing a k-nearest neighbors classifier and determining the optimal k-value
- Calculating and comparing the classification accuracies, false postive rate, and false negative rate of the two models

### Tech
- [Numpy]
- [Pandas]
- [scikit-learn]
- [XGBoost]

### Inspiration
Thanks to [Data-Flair] for providing the inspiration for and backbones of this project!
### Data
The biomedical Parkinson's data used was originally created by [Max Little], and accessed from the [UCI Machine Learning Repository].

[Numpy]: <https://numpy.org>
[Pandas]: <https://pandas.pydata.org>
[scikit-learn]: <https://scikit-learn.org/stable/#>
[XGBoost]: <https://xgboost.ai>
[Data-Flair]: <https://data-flair.training>
[Max Little]: <http://www.maxlittle.net/home/index.php>
[UCI Machine Learning Repository]: <https://archive.ics.uci.edu/ml/datasets/parkinsons>
