# Task-5-Exploratory-Data-Analysis-EDA-TITANIC-dATASET

1. Get the Titanic dataset
   The most common source is the Kaggle Titanic:Machin Leaning from Disaster dataset,which include:
   . train.csv - for model training
   . test.csv  - for prediction/evaluation

2. Load and explore data
   We'll check columns like:
   . Pclass,Sex,Age,Sibsp,Parch,Fare,Embarked - features
   . Survived - target(0=died,1=survived)

3. Preprocess
   . Fill missing values(e.g.,Age median,Embarked mode)
   . Encode categorical features (like sex and Embarked)
   . Scale numerical columns if needed

4. Train the model
   A simple baseline model could be:
   . Logistic Regression
   . Random Forest Classifier
   . XGBoost or LightGM(For higheraccuracy)

5. Evaluate
   . Use accuracy,Precision, recall,F1-Score
   . Perform cross-validation

6. Predict on the test dataset
   . Loads Titanic data
   . Preprocesses it
   . Trains a model
   . Shows accuracy & prediction results               
