# Titanic_Kaggle
# Datasets
The files train.csv and test.csv contains data about each passenger. The file train.csv is used to train the model, and the file test is used to test the model, from which we will get the predictions 
# Exploratory data analysis(EDA)
The exploratory_data_analysis.ipynb file contains data analysis, filling in missing data, identifying important features
# Machine Learning
1. The RandomForestClassifier.ipynb file uses the RandomForestClassifier ensemble model from sklearn. GridSearch is used to train the model. The accuracy of the model is measured by the accuracy metric.
2. The StackingClassifier.ipynb file uses the StackingClassifier ensemble model from sklearn. The base models were: RandomForestClassifier, GradientBoostingClassifier and SVC (support vectors), and the meta model was LogisticRegression
# Results
After submitting the predictions to Kaggle, I got the following results:

RandomForestClassifier has an accuracy on the test set of 0.77511

StackingClassifier has an accuracy of 0.77272

