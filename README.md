# 🧠 Mental Health Predictor

This project aims to predict whether employees in the tech industry require mental health treatment using survey data. By applying machine learning models to real-world data, it helps in understanding patterns and potential risk factors associated with mental health.

## 📌 Project Overview

Mental health in the workplace, especially in the tech sector, is a growing concern. This project uses the [Mental Health in Tech Survey](https://www.kaggle.com/osmi/mental-health-in-tech-survey) to analyze and predict whether an individual is likely to seek treatment for mental health issues.

## 📂 Repository Structure
MentalHealthPredictor/
├── Data/
│ └── survey.csv # Dataset used
├── Mental_Health_Prediction.ipynb # Main notebook with all code
├── README.md # Project documentation
└── .gitignore # Files to ignore during git pushes
## 📄 Research Paper

A full research paper is included and can be accessed here:  
📘 **[Mental_Health_final_paper.pdf](https://github.com/SAINATH0224/MentalHealthPredictor/blob/main/Mental_Health_Analysis.pdf)**

It covers:
- Background and motivation
- Dataset overview
- Methodology and preprocessing
- Machine learning models and evaluation
- Results, analysis, and future scope

This document can be referenced for academic or presentation purposes.

## 🔍 Dataset

- **Source**: Kaggle — OSMI Mental Health in Tech Survey  
- **Size**: ~1,250 responses  
- **Features**:  
  - Age, Gender, Country  
  - Company size, Remote work, Work interference  
  - Family history, Mental health history  
  - and more...

## 🛠️ Technologies Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn

## 🚀 Workflow

### 1. Data Preprocessing
- Dropped irrelevant columns  
- Encoded categorical variables  
- Handled missing values

### 2. Exploratory Data Analysis (EDA)
- Plotted distributions (age, gender, company size, etc.)  
- Used heatmaps and bar charts to explore patterns

### 3. Model Building
Trained and evaluated:
- Logistic Regression  
- Random Forest  
- K-Nearest Neighbors (KNN)  
- Decision Tree

> ✅ **Best Model**: Random Forest Classifier

### 4. Model Evaluation
- Compared accuracy of each model  
- (To be added): Confusion Matrix, F1-score, ROC-AUC

## 📊 Results

| Model              | Accuracy |
|-------------------|----------|
| Logistic Regression | ~78%    |
| Decision Tree       | ~81%    |
| KNN                 | ~79%    |
| **Random Forest**   | **83%** |

## 📈 Future Improvements

- Add detailed evaluation metrics  
- Perform hyperparameter tuning  
- Feature importance using SHAP  
- Deploy using Streamlit or Flask

## 📦 Installation

```bash
# 1. Clone this repository
git clone https://github.com/Sruthi1907/MentalHealthPredictor.git

# 2. Change into the project directory
cd MentalHealthPredictor

# 3. Install dependencies
pip install -r requirements.txt

# If requirements.txt is missing, install manually
pip install pandas numpy matplotlib seaborn scikit-learn

# 4. Launch the notebook
# Open 'Mental_Health_Prediction.ipynb' in Jupyter Notebook or VS Code
