# 🧠 Mental Health Treatment Predictor (Machine Learning)

This project focuses on predicting whether an individual in the tech industry is likely to seek mental health treatment using real-world survey data.  
It demonstrates a complete **machine learning pipeline** — from data preprocessing and exploratory analysis to multi-model training and evaluation.

> ⚠️ This is a **Machine Learning project (not a website)**, built to showcase data analysis, model experimentation, and result interpretation.

---

## 📌 Why this Project Matters

Mental health challenges are increasingly common in high-pressure environments like the tech industry, yet they often remain underreported.

This project:
- Analyzes demographic and behavioral factors related to mental health
- Predicts treatment-seeking behavior using ML models
- Highlights how data-driven insights can support early awareness and decision-making

---

## 📄 Research Paper

📘 **[View Full Research Paper (PDF)](https://github.com/SAINATH0224/MentalHealthPredictor/blob/main/Mental_Health_Analysis.pdf)**

The paper covers:
- Background & motivation  
- Dataset overview  
- Data preprocessing & EDA  
- Machine learning models  
- Results, analysis, and conclusions  

Suitable for **academic review, interviews, and presentations**.

---

## 📁 Project Structure

```text
MentalHealthPredictor/
│
├── Data/                         # Raw and processed datasets
│   ├── Mental_Health_Dataset.csv
│   └── Mental_Health_Dataset_processed.csv
│
├── preprocessing/                # Data cleaning and EDA scripts
│   ├── clean_mental_step1.py     # Data preprocessing & missing value handling
│   └── visualization_eda_step2.py # Exploratory Data Analysis (EDA)
│
├── models/                       # Machine learning model implementations
│   ├── logistic_mental_step3.py  # Logistic Regression model
│   ├── decision_mental_step4.py  # Decision Tree classifier
│   ├── random_mental_step5.py    # Random Forest classifier
│   ├── knn_mental_step6.py       # K-Nearest Neighbors (KNN)
│   ├── support_mental_step7.py   # Support Vector Machine (SVM)
│   └── ensemble_method_mental_step8.py # Voting Ensemble model
│
├── Results/                      # Model evaluation outputs
│   ├── logistic_regression_results.xlsx
│   ├── decision_tree_results.xlsx
│   ├── random_forest_results.xlsx
│   ├── knn_results.xlsx
│   ├── svm_results.xlsx
│   └── ensemble_results.xlsx
│
├── Mental_Health_Analysis.pdf    # Detailed research paper & analysis
├── README.md                     # Project documentation
└── .gitignore                    # Ignored files

```

---

## 🔍 Dataset

- **Source**: Kaggle – OSMI Mental Health in Tech Survey  
- **Domain**: Mental Health, Workplace Analytics  
- **Target Variable**: `treatment` (Yes / No)

### Key Features
- Gender, Country, Occupation  
- Self-employed status  
- Family history of mental illness  
- Stress levels, mood swings, coping struggles  
- Work interest, social interaction  
- Access to mental health care options  

---

## 🛠️ Tech Stack

- **Language**: Python  
- **Data Processing**: Pandas, NumPy  
- **Visualization**: Matplotlib, Seaborn  
- **Machine Learning**: Scikit-learn  

---

## 🚀 Workflow

### 1️⃣ Data Preprocessing
- Converted categorical features to proper data types  
- Handled missing values (mode for categorical, mean for numerical)  
- Removed irrelevant columns  
- Applied one-hot encoding  

### 2️⃣ Exploratory Data Analysis (EDA)
- Distribution analysis of categorical variables  
- Visualization of treatment trends across demographics  
- Identification of key behavioral indicators  

### 3️⃣ Model Building
Each model was trained independently using:
- Feature selection (`SelectKBest`)  
- 3-fold and 5-fold cross-validation  
- 80–20 train-test split  

Models implemented:
- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  
- K-Nearest Neighbors (KNN)  
- Support Vector Machine (SVM)  
- Voting Ensemble Model  

### 4️⃣ Model Evaluation
Models were evaluated using:
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Mean Squared Error (MSE)  
- Mean Absolute Error (MAE)  

All results are saved as **Excel files** for comparison.

---

## 📊 Results Summary

| Model               | Accuracy (Approx.) |
|--------------------|-------------------|
| Logistic Regression | ~78% |
| KNN                | ~79% |
| Decision Tree      | ~81% |
| SVM                | ~80% |
| **Random Forest**  | **~83%** |
| Ensemble Model     | ~82% |

✅ **Best Performing Model**: **Random Forest Classifier**

---

## 🧠 Key Insights

- Behavioral and workplace factors strongly influence treatment-seeking behavior  
- Tree-based models outperform linear models on this dataset  
- Ensemble models improve stability  
- Feature selection and validation significantly impact performance  

---

## 🔮 Future Improvements

- Hyperparameter tuning (GridSearchCV / RandomizedSearchCV)  
- Feature importance using SHAP  
- ROC-AUC and confusion matrix analysis  
- Optional deployment using Streamlit  

---

## 📦 Run Locally

```bash
git clone https://github.com/SAINATH0224/MentalHealthPredictor.git
cd MentalHealthPredictor
pip install pandas numpy matplotlib seaborn scikit-learn
python models/random_mental_step5.py
👤 Author

Sainath Goud
B.Tech – Computer Science & Engineering (Data Science)
Machine Learning | Data Analysis | Applied AI

📌 This repository is part of my academic and machine learning portfolio.
