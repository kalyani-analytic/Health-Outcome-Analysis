# Healthcare Risk Stratification App

A machine learning web application built with Streamlit that predicts the risk 
of complicated outcomes or death for hospital patients based on clinical data.

## Features
- Predicts risk level (Low / Moderate / High) with probability score
- Interactive gauge chart for visual risk representation
- Feature contribution chart showing which factors drive the prediction
- Live abnormal lab value detection (Blood Sugar, Cholesterol, Hemoglobin)
- ROC curve display for model performance evaluation
- Input validation and clinical disclaimer

## Tech Stack
- Python, Streamlit, Scikit-learn, Plotly, Pandas, NumPy

## Model
Logistic Regression trained on 4 features:
- Age
- Length of Stay
- Treatment Cost
- Abnormal Lab Count

## How to Run
1. Install dependencies: pip install -r requirements.txt
2. Train the model:     python train_model.py
3. Launch the app:      streamlit run app.py

## Disclaimer
This tool is for decision support only and is not a substitute 
for professional medical judgment.
