🧠 Mental Health Treatment Outcome Predictor
A machine learning-based application designed to predict whether individuals are likely to seek mental health treatment, based on demographic and behavioral attributes. This project focuses on university students and IT professionals, aiming to aid early identification and intervention strategies.

📘 Overview
This project systematically evaluates the performance of six machine learning models on a mental health survey dataset. It explores key demographic and behavioral predictors and helps derive actionable insights to enhance mental health support systems.

🛠️ Features
Predicts likelihood of seeking mental health treatment

Handles a wide range of features: gender, occupation, mental health history, and more

Uses six classification algorithms:

Logistic Regression

K-Nearest Neighbors (KNN)

Decision Tree

Random Forest

Support Vector Machine (SVM)

Ensemble (Voting Classifier)

Performance evaluated using:

Accuracy

Precision

Recall

F1-score

Balanced Classification Accuracy (BCA)

🗃️ Dataset
Sourced from Kaggle

Data includes:

Demographics: Gender, Age, Country, Occupation

Behavioral: Mood swings, Stress levels, Coping struggles

History: Family mental health, Previous treatment

Care access: Participation in interviews, Accessibility

🔍 Exploratory Data Analysis
Count plots and histograms for visualizing variable distributions

Correlation heatmaps to explore inter-feature relationships

Analysis of treatment-seeking trends across different demographics

🧪 Model Building & Evaluation
➤ Preprocessing
Categorical variable encoding

Handling missing values

Feature selection with SelectKBest

➤ Model Training
Training-test split: 80-20

k-Fold Cross-Validation (k = 3 and 5)

Metrics computed: Accuracy, MSE, MAE, R², Precision, Recall, F1-score, Specificity

➤ Best Performing Models
Random Forest and Decision Tree achieved top accuracy of 72.5%

Ensemble method provided robust but slightly lower accuracy

📊 Results
Model	Accuracy
Random Forest	0.725
Decision Tree	0.725
Logistic Regression	~0.69
SVM	~0.68
KNN	~0.67
Ensemble	~0.71
