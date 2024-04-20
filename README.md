# Titanic-Survival-Prediction
This Repository contains a predictive model developed using data science techniques to determine the likelihood of survival for passengers aboard the Titanic. The project encompasses various stages of the data science pipeline, starting from data preprocessing to model evaluation and prediction.

Data Preprocessing:

The dataset is loaded from a CSV file using pandas.
Data exploration and descriptive statistics are performed to understand the dataset.
Correlation analysis is conducted to identify relationships between numeric features.

Model Development:

Stratified shuffle split is used for train-test split to maintain class distribution.
Custom transformers are implemented for data preprocessing tasks such as imputation and feature encoding.
A pipeline is constructed to streamline the preprocessing workflow.
Standard scaling is applied to numeric features.
RandomForestClassifier is selected as the model for prediction.

Model Training and Evaluation:

Grid search is employed for hyperparameter tuning using cross-validation.
The best performing model is selected based on accuracy.
The model is trained on the training set and evaluated on the test set.
Finally, the model is applied to new data for prediction.

Result Output:

Predictions are made on the test dataset.
The predictions are saved along with the PassengerId in a CSV file for submission.

Dependencies:

pandas
numpy
matplotlib
seaborn
scikit-learn

Usage:

Clone the repository.
Ensure dependencies are installed.
Run the provided Python script to train the model and generate predictions.

Note: This code serves as a basic example of Titanic survival prediction and can be extended for further experimentation and improvement.
