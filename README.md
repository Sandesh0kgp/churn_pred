

# Customer Churn Prediction App

A simple Streamlit app to predict customer churn using a pre-trained TensorFlow model.

## Features
- Input customer details (e.g., geography, gender, age, balance, etc.).
- Predicts churn probability and likelihood.

## Requirements
- Python 3.x
- Libraries: `streamlit`, `numpy`, `tensorflow`, `sklearn`, `pandas`, `pickle`

## Setup
1. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
2. Ensure pre-trained files (`model.h5`, `label_encoder_gender.pkl`, `onehot_encoder_geo.pkl`, `scaler.pkl`) are in the same directory.

## Usage
1. Run the app:  
   ```bash
   streamlit run app.py
   ```
2. Enter customer details in the UI.
3. View churn prediction and probability.

## Files
- `app.py`: Main application script.
- `model.h5`: Trained TensorFlow model.
- `*.pkl`: Pre-trained encoders and scaler.

--- 

