# Chronic Kidney Disease Classifier

This repository contains a machine learning project for predicting Chronic Kidney Disease (CKD) from patient health data. The workflow is implemented primarily using Jupyter notebooks and compares several classification algorithms to identify the most effective model.

## Project Overview

The goal of this project is to build and evaluate classification models that can predict whether a patient may have chronic kidney disease based on clinical attributes such as blood pressure, albumin, red blood cell count, and other diagnostic indicators.

## Repository Structure

```text
.
├── CKD-Prediction/
│   ├── 01_data/
│   │   └── CKD.csv
│   ├── 02_notebooks/
│   │   ├── decision_tree_classification_grid.ipynb
│   │   ├── logistic_regression_classification_grid.ipynb
│   │   ├── random_forest_classification_grid.ipynb
│   │   └── svm_classification_grid.ipynb
│   ├── 03_outputs/
│   ├── 04_reports/
│   │   └── CKD_Prediction_Report_Madhu.pdf
│   ├── requirements.txt
│   └── README.md (optional project-level documentation)
└── README.md
```

## Models Included

The project experiments with the following classification models:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)

These notebooks are designed to compare model performance and tune parameters for better predictive accuracy.

## Data

The dataset used in this project is stored in:

- `CKD-Prediction/01_data/CKD.csv`

It contains patient-related medical features used for CKD prediction.

## Setup

1. Clone the repository:

```bash
git clone https://github.com/Lahu-Dhotre/chronic-kidney-disease-classifier-main.git
cd chronic-kidney-disease-classifier-main
```

2. Create and activate a virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate
```

On Windows:

```bash
.venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install -r CKD-Prediction/requirements.txt
```

## Run the Notebooks

Open the notebooks in `CKD-Prediction/02_notebooks/` using Jupyter Notebook or JupyterLab:

```bash
jupyter notebook
```

Then navigate to the relevant notebook and run the cells in order.

## Outputs

- Model outputs and intermediate artifacts can be stored in `CKD-Prediction/03_outputs/`
- Evaluation reports and documentation are placed in `CKD-Prediction/04_reports/`

## Requirements

The project dependencies are listed in:

- `CKD-Prediction/requirements.txt`

These include data science and machine learning packages such as `pandas`, `numpy`, `scikit-learn`, and visualization libraries.

## License

This project is intended for educational and research use unless otherwise specified by the repository owner.

## Author

Lahu Dhotre
