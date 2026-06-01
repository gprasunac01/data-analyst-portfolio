## Objective
Predict whether a candidate is likely to look for a new job using HR data  
(city, experience, education, company size, etc.).

## Tech stack
- Python (pandas, numpy, matplotlib, seaborn, scikit-learn, imbalanced-learn)
- Jupyter Notebook

## Steps
- Data cleaning and handling missing values
- Encoding categorical variables
- Handling class imbalance with SMOTE
- Training Logistic Regression and Random Forest models
- Evaluating using accuracy, precision, recall, F1-score, and ROC-AUC
- Feature importance analysis to interpret key drivers of job change

## Files
- `HR_Job_Change_Prediction.ipynb` – main analysis and model notebook
- `data/` – training & test datasets
- `outputs/` – charts (confusion matrix, ROC curve, feature importance)
