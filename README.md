# Molecular Melting Point Prediction using RDKit and Machine Learning

## Overview

This project explores the prediction of **molecular melting points** using **RDKit** for molecular feature extraction and **Machine Learning** for regression modeling.

The objective is to investigate how well molecular descriptors and fingerprints generated from chemical structures (SMILES) can predict experimental melting points.

This repository is part of my learning journey in **Machine Learning**, **Cheminformatics**, and **Computational Chemistry**.

---

## Objectives

* Explore and understand a real-world molecular dataset.
* Generate molecular descriptors using RDKit.
* Build baseline and advanced regression models.
* Compare different feature representations.
* Evaluate model performance using standard regression metrics.
* Develop an interpretable and reproducible machine learning workflow.

---

## Dataset

**Dataset:** Jean-Claude Bradley Open Melting Point Dataset

The dataset contains experimentally measured melting points along with molecular information.

**Target Variable**

* Melting Point (°C)

**Primary Molecular Representation**

* SMILES

> The dataset used in this repository is provided for research and educational purposes. Please refer to the original dataset source for licensing information.

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* RDKit
* Scikit-learn

Future additions may include:

* XGBoost
* LightGBM
* CatBoost
* PyTorch
* SHAP

---

## Project Workflow

1. Load the dataset
2. Inspect and clean the data
3. Perform Exploratory Data Analysis (EDA)
4. Convert SMILES into RDKit molecular objects
5. Generate molecular descriptors and fingerprints
6. Prepare features for machine learning
7. Train regression models
8. Compare model performance
9. Interpret model predictions
10. Summarize findings

---

## Repository Structure

```text
.
├── melting-point.ipynb
├── melting-point.xlsx
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Evaluation Metrics

The models will be evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## Current Status

* [ ] Dataset selected
* [ ] Data exploration
* [ ] Data cleaning
* [ ] RDKit preprocessing
* [ ] Descriptor generation
* [ ] Feature engineering
* [ ] Model training
* [ ] Hyperparameter tuning
* [ ] Model interpretation
* [ ] Final evaluation

---

## Future Improvements

* Molecular fingerprint comparison
* Feature selection
* Hyperparameter optimization
* Explainable AI using SHAP
* Graph Neural Networks (GNNs)
* Comparison with published benchmark models

---

## Learning Goals

This project is intended to strengthen practical skills in:

* Machine Learning
* Data Analysis
* Cheminformatics
* Molecular Property Prediction
* Scientific Python
* Reproducible Research

---

## Author

**Dhawal Panchamiya**

BS-MS Natural Sciences
IISER Bhopal

---

## License

This repository is released under the NO 
License.
