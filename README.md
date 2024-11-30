# Problematic Internet Use Prediction

## Overview

This project addresses the growing concern of problematic internet use among children and adolescents by developing a machine learning model to predict the Severity Impairment Index (SII). Leveraging a combination of tabular and time-series data, the model integrates statistical features, engineered features, and actigraphy-based latent representations to improve prediction accuracy. The project implements advanced techniques such as KNN imputation, Autoencoder-based dimensionality reduction, and PySpark pipelines for large-scale data processing.

Key contributions of this project include:
- Feature engineering to create meaningful predictors from raw data.
- Use of PySpark for efficient data processing and model training.
- Evaluation using the Quadratic Weighted Kappa (QWK) score to measure model agreement with the target variable.

## Features

- Data preprocessing: Handling missing data and removing redundant features.
- Feature engineering: Statistical and derived features from actigraphy time-series data.
- Model training: Logistic Regression implemented in PySpark.
- Evaluation: QWK score to assess ordinal prediction performance.

## Appendix

This project was developed and tested on a local machine with the following configuration:
- **Operating System**: Windows 11
- **IDE**: VSCode with IPyKernel
- **Processor**: AMD Ryzen 7 5800H

### Dependencies

The following dependencies are required to run the project:
- Python (3.8+)
- PySpark
- Torch
- Pandas
- Numpy
- Matplotlib
- TQDM
- Scikit-learn
- XGBoost (for Spark)

Install all dependencies via `pip install -r requirements.txt` (if applicable).
