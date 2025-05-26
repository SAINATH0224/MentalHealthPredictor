# Mental Health Treatment Outcome Predictor

This project uses machine learning to predict the likelihood of individuals seeking mental health treatment. The dataset contains demographic and behavioral data and aims to help organizations and institutions support individuals more effectively.

## Overview

This repository contains code for analyzing a mental health survey dataset and building predictive models. The primary goal is to evaluate the effectiveness of multiple classification algorithms to identify patterns related to treatment-seeking behavior.

## Features

* Predicts likelihood of mental health treatment.
* Analyzes a wide range of features such as gender, occupation, mental health history, etc.
* Applies and compares the following classifiers:

  * Logistic Regression
  * K-Nearest Neighbors (KNN)
  * Decision Tree
  * Random Forest
  * Support Vector Machine (SVM)
  * Ensemble Voting Classifier
* Evaluates models using:

  * Accuracy
  * Precision
  * Recall
  * F1-score
  * Balanced Classification Accuracy (BCA)

## Dataset

* Source: [Kaggle](https://www.kaggle.com/)
* Includes:

  * Demographic data (age, gender, country, occupation)
  * Mental health indicators (family history, stress, mood swings, coping ability)
  * Treatment-related behavior (care options, interviews, willingness to seek treatment)

## Exploratory Data Analysis

* Count plots for categorical variables
* Histograms for numeric variables
* Heatmaps for correlation analysis
* Distribution comparison of treated vs non-treated participants

## Methodology

1. **Data Preprocessing**

   * Handle missing values
   * Encode categorical variables
   * Feature selection using SelectKBest with f\_regression

2. **Model Training**

   * Train-test split: 80/20
   * Applied 3-fold and 5-fold cross-validation
   * Used metrics like Accuracy, Precision, Recall, F1-Score

3. **Model Evaluation**

   * Evaluated all six models on test set
   * Logged top results and metrics to Excel for reference

## Results

| Model               | Accuracy |
| ------------------- | -------- |
| Random Forest       | 0.725    |
| Decision Tree       | 0.725    |
| Logistic Regression | \~0.69   |
| SVM                 | \~0.68   |
| KNN                 | \~0.67   |
| Ensemble            | \~0.71   |

## Conclusion

Tree-based models (Random Forest, Decision Tree) delivered the highest performance with 72.5% accuracy. Ensemble methods offered robust results but slightly lower than individual tree models. These models can be a helpful tool in designing mental health support systems for specific populations like students and IT professionals.

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/yourusername/mental-health-predictor.git
   cd mental-health-predictor
   ```

2. Install dependencies:

   ```
   pip install -r requirements.txt
   ```

3. Run the notebook:

   ```
   jupyter notebook Mental_Health_Predictor.ipynb
   ```

## Repository Structure

```
mental-health-predictor/
├── data/
│   └── mental_health.csv
├── notebooks/
│   └── Mental_Health_Predictor.ipynb
├── results/
│   └── model_results.xlsx
├── visuals/
│   └── plots/
├── README.md
└── requirements.txt
```

## References

1. Abdul Rahman et al., *Machine Learning-Based Prediction of Mental Well-Being*
2. PRISMA 2020 Systematic Review Guidelines
3. Machine Learning Approaches in Predicting Mental Health Problems
4. Dr. J. Arokia Renjit et al., *Prediction of Mental Health Using ML*


