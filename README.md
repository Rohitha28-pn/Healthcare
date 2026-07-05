# Healthcare Readmission Risk Prediction System

## Overview

This project is a machine learning-based Healthcare Readmission Risk Prediction System developed using Python and Scikit-learn. It predicts whether a patient is at high risk of hospital readmission based on demographic information, vital signs, laboratory results, and medical history.

The notebook automatically generates a synthetic healthcare dataset, trains a Random Forest classification model, evaluates its performance, and provides an interactive interface for predicting the readmission risk of new patients.

---

## Features

- Synthetic healthcare dataset generation
- Data preprocessing
  - Missing value imputation
  - Feature scaling
  - One-hot encoding
- Random Forest Classifier
- Hyperparameter tuning using RandomizedSearchCV
- Model evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - ROC-AUC
- ROC Curve visualization
- Precision-Recall Curve visualization
- Save trained model using Joblib
- Interactive patient risk prediction using ipywidgets

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Joblib
- ipywidgets
- Google Colab / Jupyter Notebook

---

## Project Workflow

1. Generate synthetic patient dataset
2. Preprocess numerical and categorical features
3. Split dataset into training and testing sets
4. Build preprocessing pipeline
5. Train Random Forest model
6. Tune model hyperparameters
7. Evaluate model performance
8. Save trained model
9. Predict readmission risk for new patient records

---

## Dataset Features

The synthetic dataset contains patient information such as:

- Age
- Gender
- BMI
- Blood Pressure
- Heart Rate
- Body Temperature
- Oxygen Saturation
- Respiratory Rate
- Hemoglobin
- White Blood Cell Count
- Creatinine
- Blood Glucose
- Sodium
- Potassium
- Diabetes
- Hypertension
- Congestive Heart Failure
- Chronic Kidney Disease
- COPD
- Prior Admissions
- Number of Medications
- Smoking Status
- Physical Activity Level

Target Variable:

- Readmission Risk (High / Low)

---

## Installation

Install the required libraries:

```bash
pip install scikit-learn pandas matplotlib ipywidgets joblib
```

---

## Running the Project

Open the notebook in:

- Google Colab
- Jupyter Notebook

Run all cells sequentially.

The notebook will:

- Generate the dataset
- Train the model
- Evaluate the model
- Save the trained model
- Launch the interactive prediction interface

---

## Model Evaluation Metrics

The notebook reports:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score

It also visualizes:

- ROC Curve
- Precision-Recall Curve

---

## Model Output

The trained model is saved as:

```
readmission_model.joblib
```

This model can later be loaded for inference without retraining.

---

## Applications

- Hospital readmission prediction
- Clinical decision support
- Patient risk assessment
- Healthcare analytics
- Medical research
- Predictive healthcare systems

---

## Future Improvements

- Train using real-world hospital datasets
- Deploy using Flask or FastAPI
- Build a Streamlit web application
- Integrate with Electronic Health Records (EHR)
- Explain predictions using SHAP or LIME
- Support deep learning models for improved accuracy

---

## License

This project is intended for educational and research purposes only.

---

## Author

Developed as a Healthcare Machine Learning project using Python and Scikit-learn.
