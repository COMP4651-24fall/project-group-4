# Problematic Internet Use Prediction

## Overview

This project aims to predict the Severity Impairment Index (SII) as part of the [Kaggle Competition: Child Mind Institute - Problematic Internet Use](https://www.kaggle.com/competitions/child-mind-institute-problematic-internet-use). The competition challenges participants to develop models capable of analyzing children's physical activity data to detect early indicators of problematic internet and technology use.

Leveraging a combination of tabular and time-series data, the project integrates statistical features, engineered features, and actigraphy-based latent representations to improve prediction accuracy. Advanced machine learning techniques and PySpark pipelines were utilized for data preprocessing and model training.

Key contributions of this project include:
- Comprehensive data preprocessing, including handling missing values and redundant features.
- Robust feature engineering from actigraphy data, transforming time-series data into actionable features.
- Efficient model training and evaluation using PySpark and PyTorch, with results assessed via the Quadratic Weighted Kappa (QWK) score.

## Features

- **Data Preprocessing**: Managing missing values, imputations, and redundant features.
- **Feature Engineering**: Statistical, derived, and actigraphy-based features for improved predictions.
- **Model Training**: Logistic Regression model implemented using PySpark MLlib.
- **Evaluation**: Performance evaluated using the Quadratic Weighted Kappa (QWK) score, which accounts for the ordinal nature of the target variable.

## Kaggle Competition Link

You can learn more about the competition [here](https://www.kaggle.com/competitions/child-mind-institute-problematic-internet-use).
You can download the raw datas from:
https://drive.google.com/drive/folders/1PCV8kkYhH1qHmKoJOjjsvJVKbASkiAq6?usp=drive_link

## Appendix

This project was developed and tested on a local machine with the following configuration:
- **Operating System**: Windows 11
- **IDE**: VSCode with IPyKernel
- **Processor**: AMD Ryzen 7 5800H

### Dependencies
The following app are required to build environment:
Spark = 3.5.3
Java = jre1.8.0_431

tutorial:
https://youtu.be/OmcSTQVkrvo?si=C_TkPIePhm0W1WtC

The following dependencies are required to run the project:
- Python (3.9)
- PySpark
- Torch
- Pandas
- Numpy
- Matplotlib
- TQDM
- Scikit-learn
- XGBoost (for Spark)

Install all dependencies via `pip install -r requirements.txt` (if applicable).
