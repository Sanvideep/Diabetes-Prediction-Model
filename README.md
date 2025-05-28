# Diabetes-Prediction-Model
This project presents a machine learning model designed to predict the likelihood of diabetes in a patient based on key medical parameters. The dataset used is a well-known diabetes dataset, containing several diagnostic features and one target variable, Outcome, which indicates whether a patient has diabetes (1) or not (0).

#Dataset Features:
Pregnancies: Number of times the patient has been pregnant
Glucose: Plasma glucose concentration after 2 hours in an oral glucose tolerance test
BloodPressure: Diastolic blood pressure (mm Hg)
SkinThickness: Triceps skin fold thickness (mm)
Insulin: 2-hour serum insulin (mu U/ml)
BMI: Body Mass Index (weight in kg/(height in m)^2)
DiabetesPedigreeFunction: A function that scores the likelihood of diabetes based on family history
Age: Age of the patient in years
Outcome: Target variable — 1 indicates diabetes, 0 indicates no diabetes

#Machine Learning Workflow:
The notebook includes the following steps:
Data Preprocessing: Handling missing values and normalizing data
Exploratory Data Analysis (EDA): Visualizing distributions and correlations
Model Training: Using multiple classification algorithms:
Logistic Regression
Decision Tree
Random Forest
K-Nearest Neighbors (KNN)
Support Vector Machine (SVM)
Model Evaluation: Evaluating performance using accuracy, confusion matrix, classification report, and ROC-AUC curve

