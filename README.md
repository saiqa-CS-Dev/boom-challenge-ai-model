# Boom Challenge AI Model

## Overview
This repository contains a machine learning model developed for the Boom Challenge. It implements forward prediction and inverse design using data-driven techniques.

---

## Model Details

### Forward Prediction
- Algorithm: XGBoost Regressor
- Purpose: Predict target outputs from input features
- Trained on provided dataset

### Inverse Design
- Method: Constraint-based sampling
- Purpose: Generate valid input configurations that satisfy target outputs

---

## Files

- prediction_submission.csv → Forward prediction results  
- inverse_submission.csv → Inverse design results  
- models.pkl → Trained machine learning model  

---

## Usage

```python
import pickle

model = pickle.load(open("models.pkl", "rb"))
