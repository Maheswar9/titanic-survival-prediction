Titanic Survival Prediction
Project Overview

This project is an end-to-end machine learning solution to predict the survival of passengers on the Titanic. The goal is to demonstrate a complete data science workflow, including data exploration, feature engineering, model training, and evaluation.
Dataset Details

The project uses the Titanic dataset from Kaggle. The features include:

    Survived: The target variable. 0 means the passenger did not survive, while 1 means they survived.

    Pclass: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd).

    Name, Sex, Age: Self-explanatory.

    SibSp: Number of siblings & spouses of the passenger aboard the Titanic.

    Parch: Number of children & parents of the passenger aboard the Titanic.

    Ticket: Ticket ID.

    Fare: Price paid for the ticket.

    Cabin: Passenger's cabin number.

    Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

Project Workflow

    Data Exploration: The dataset is initially explored to understand its structure, data types, and identify missing values.

    Data Preprocessing Pipeline: A robust pipeline is built using Scikit-learn to clean and prepare the data for machine learning models. This includes separate steps for numerical and categorical features.

    Model Training and Evaluation: Two models, a Support Vector Classifier (SVC) and a Random Forest Classifier, are trained and evaluated using 10-fold cross-validation to ensure a reliable measure of performance.

    Prediction: The best-performing model is used to make predictions on the unseen test data.

Final Results

The Random Forest Classifier achieved the highest accuracy at 81.3% and was chosen as the final model.

    Support Vector Classifier Mean Accuracy: 73.3%

    Random Forest Mean Accuracy: 81.3%

This project demonstrates a complete and robust workflow for solving a classification problem.