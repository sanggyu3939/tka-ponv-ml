# Prediction of PONV after total knee arthroplasty

This repository contains the analytical code accompanying the manuscript **“Prediction of postoperative nausea and vomiting within 24 hours after total knee arthroplasty using interpretable machine learning.”**

## Contents

- `PONV_TKA_reproducible_analysis.ipynb`: complete model-development, evaluation, explainability, and temporal-validation workflow
- `data_dictionary.csv`: predictor definitions and coding scheme
- `example_input.csv`: schema-only example input containing no patient data
- `requirements.txt`: Python dependencies

## Reproducibility

The analysis uses a stratified 80/20 training–test split and stratified five-fold cross-validation within the training set. A random seed of 42 is used. Fixed hyperparameter settings are applied consistently across the three hierarchical feature sets; no data-driven hyperparameter search was performed.

## Data availability

Patient-level clinical data are not publicly available because of institutional privacy and data-protection restrictions. No patient-level observations or predictions are included in this repository.

## Intended use

The code is provided for research reproduction and independent evaluation. The models are not intended for direct clinical decision-making without external and prospective validation.

## Authors

Sang Gyu Kwak, Jae Bum Kwon, Inyoung Jung, Hyunsoo Kang, and Won Kee Choi  
Daegu Catholic University, Daegu, Republic of Korea
