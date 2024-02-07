# Cancer Prediction Model 
Loads a dataset from the UCI Machine Learning Repository.
Drops the unnecessary column 'ID' from the dataset.
Transforms the non-numeric target column 'Diagnosis' into numeric form using LabelEncoder.
Splits the dataset into training and testing sets.
Initializes and trains a Logistic Regression model.
Makes predictions on the training and testing sets.
Evaluates the model performance using Mean Squared Error and R2 Score.
Displays logistic regression results in a DataFrame.
Displays the Classification Report for the testing set.
Visualizes the actual vs. predicted values using a bar plot.s