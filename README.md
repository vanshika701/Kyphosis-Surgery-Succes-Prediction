# Kyphosis Surgery Success Prediction

A machine learning project to predict the success of kyphosis corrective surgery using patient characteristics

## 📋 Project Overview

Kyphosis is a spinal condition characterized by an excessive forward rounding of the upper back. While corrective surgery is often performed to treat kyphosis, the condition may persist after the operation in some cases. 
## 🎯 Objective

The primary goal is to develop a machine learning model that can predict the likelihood of kyphosis persisting after corrective spinal surgery, helping medical professionals make informed decisions about treatment approaches and patient care.

## 📊 Dataset

The dataset contains information about patients who underwent kyphosis corrective surgery. 

### Features:
- **Age**: Age of the patient in months
- **Number**: Number of vertebrae involved in the operation
- **Start**: Starting vertebrae level where the operation begins (topmost vertebra operated on)
- **Kyphosis**: Target variable indicating whether kyphosis was present after surgery (absent/present)

### Dataset Statistics:
- Total records: 81 patients
- Features: 3 input variables + 1 target variable
- Target classes: Binary (absent/present)

## 🔧 Technology Stack

- **Programming Language**: Python
- **Libraries**: 
  - Pandas (Data manipulation)
  - NumPy (Numerical computing)
  - Scikit-learn (Machine learning)
  - Matplotlib/Seaborn (Data visualization)
  - Jupyter Notebook (Development environment)

## 🤖 Machine Learning Approach

### Algorithms Implemented:
- **Decision Trees**: For interpretable rule-based predictions
- **Random Forest**: Ensemble method for improved accuracy
- **Logistic Regression**: For probabilistic binary classification

### Model Evaluation Metrics:
- Accuracy
- Precision
- Recall (Sensitivity)
- F1-Score
- Confusion Matrix

## 📁 Project Structure

```
Kyphosis-Surgery-Success-Prediction/
├── data/
│   └── kyphosis.csv
├── notebooks/
│   └── kyphosis_analysis.ipynb
├── src/
│   ├── data_preprocessing.py
│   ├── model_training.py
│   └── evaluation.py
├── models/
│   └── trained_models/
├── results/
│   └── visualizations/
├── requirements.txt
└── README.md
```

## 🔍 Methodology

1. **Data Exploration**: Understanding the dataset structure and distributions
2. **Data Preprocessing**: Handling missing values and feature scaling
3. **Feature Analysis**: Correlation analysis and feature importance
4. **Model Training**: Training multiple algorithms with hyperparameter tuning
5. **Model Evaluation**: Comparing performance metrics across different models
6. **Model Selection**: Selecting the best performing model
7. **Validation**: Cross-validation and testing on unseen data




*Note: This model is for educational and research purposes only. Always consult with qualified medical professionals for clinical decisions.*
