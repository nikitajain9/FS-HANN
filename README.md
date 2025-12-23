# FS-HANN: Feature-Sensitive Hybrid Artificial Neural Network

## Overview
FS-HANN is a Feature-Sensitive Hybrid Artificial Neural Network designed for
predicting cardiovascular disease using the BRFSS 2015 dataset.
The model focuses on achieving high recall while maintaining computational efficiency.

## Dataset
- Source: BRFSS 2015 (CDC)
- Task: Binary classification (CVD / No CVD)
- Number of features used: 15 (after feature selection)
- Class imbalance handled using class weights

> Dataset is not included in this repository due to size constraints.

## Model Architecture
- Input layer with selected features
- Feature-sensitive hidden layers
- Hybrid ANN design
- Sigmoid output layer

## Results
- AUC: 0.8476
- Recall: 0.8067
- Reduced training time compared to baseline ANN

## How to Run
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
