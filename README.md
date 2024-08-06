# Poisonous-Mushroom-classification

Binary classification on [this](https://www.kaggle.com/datasets/carlmcbrideellis/tertiary-mushroom-1-million-more-mushrooms/data) dataset from Kaggle. For this data I treated the NA values as their own category because it worked best for the models and seemed like having no value gave some information as well.

After properly scaling and working with the different variables I trained Random Forest, Logistic Regression and XGBoost models and tested them on the test data. Calculating each of the accuracies resulted in the Random Forest being the best model with a perfect guess on the dataset.
