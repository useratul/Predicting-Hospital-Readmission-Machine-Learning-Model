# Predicting Hospital Readmission Machine Learning Model

## About Dataset
We have access to ten years of patient information.
This file is a 10 year history of hospital readmission data delineated by various measures of diabetes diagnosis.

## Information about the features
- "age" - age bracket of the patient
- "time_in_hospital" - days (from 1 to 14)
- "n_procedures" - number of procedures performed during the hospital stay
- "n_lab_procedures" - number of laboratory procedures performed during the hospital stay
- "n_medications" - number of medications administered during the hospital stay
- "n_outpatient" - number of outpatient visits in the year before a hospital stay
- "n_inpatient" - number of inpatient visits in the year before the hospital stay
- "n_emergency" - number of visits to the emergency room in the year before the hospital stay
- "medical_specialty" - the specialty of the admitting physician
- "diag_1" - primary diagnosis (Circulatory, Respiratory, Digestive, etc.)
- "diag_2" - secondary diagnosis
- "diag_3" - additional secondary diagnosis
- "glucose_test" - whether the glucose serum came out as high (> 200), normal, or not performed
- "A1Ctest" - whether the A1C level of the patient came out as high (> 7%), normal, or not performed
- "change" - whether there was a change in the diabetes medication ('yes' or 'no')
- "diabetes_med" - whether a diabetes medication was prescribed ('yes' or 'no')
- "readmitted" - if the patient was readmitted at the hospital ('yes' or 'no')

## Tools/Software
- Jupyter Notebook
- Python

## Business Context:
You are tasked with predicting whether a patient is likely to be readmitted to the hospital within 30 days based on historical patient data.

## Task Overview:
- Dataset Selection & Preprocessing
- Model Building:
	> - Build a Logistic Regression model using Python (libraries like Scikit-learn) to classify whether a patient will be readmitted.
	> - Split the data into 70% training and 30% testing.
- Model Evaluation:
	> - Evaluate the model using metrics like Accuracy, Precision, Recall, and F1-score.
	> - Briefly explain why you chose Logistic Regression and how it performs on this task.
- Theoretical Task

## Deliverables:
● Code:
- Submit a Python notebook (.ipynb) with all your code, from data preprocessing to model evaluation.
- Make sure the notebook is well-documented, with comments explaining each step.