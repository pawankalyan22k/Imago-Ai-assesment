# Imago-Ai-assesment
# Imago AI Mycotoxin Prediction in Corn using Hyperspectral Imaging

## Overview

This project addresses the task of predicting mycotoxin levels (specifically DON concentration, vomitoxin_ppb) in corn samples using hyperspectral imaging data. The project utilizes machine learning techniques to analyze spectral reflectance data and build a regression model to estimate DON concentration.

This repository contains the code, data (if permissible to share a sample, otherwise describe data source and format), and documentation for the project, as part of the Imago AI ML Intern assessment.

## Repository Structure

The repository is organized as follows:

- Imago Ai assesment/ (Root directory of the project)
    - README.md (This README file - project overview and instructions)
    - Imago Ai assesment.ipynb (Jupyter Notebook with project code)
    - TASK-ML-INTERN.csv (Dataset file - hyperspectral data. See README for data description if not included)
    - [Optional: data directory]/ (If dataset is large or separate)
        - your_dataset.csv (Dataset file - if stored in data directory)
    - [Optional: models directory]/ (If you save trained models)
        - best_xgboost_model.pkl (Example: Saved XGBoost model file)
    - [Optional: images directory]/ (If you have images for documentation)
        - scree_plot.png (Example: Scree plot visualization image)

*   **`README.md`**: This file, providing a project overview and instructions.
*   **`Imago Ai assesment.ipynb`**:  Jupyter Notebook containing the Python code for data preprocessing, dimensionality reduction (PCA), model training (FFNN, CNN, LSTM, XGBoost), and model evaluation.
*   **`TASK-ML-INTERN.csv` (or data directory)**: [**If possible to share a sample**]  The dataset file in CSV format. [**If not possible to share data directly, replace this with a clear description of the dataset source, format, and features.** For example: "The dataset used is a compact hyperspectral dataset of corn samples, provided as part of the Imago AI assessment. It is a CSV file named `TASK-ML-INTERN.csv` containing spectral reflectance data across 448 wavelength bands (columns '0' to '447') and the target variable 'vomitoxin_ppb' (DON concentration) in the last column. The first column 'hsi_id' is a sample identifier." ]
*   **`models/` (optional)**: Directory to store any saved trained models (e.g., using `joblib.dump` for scikit-learn/XGBoost models or `model.save()` for Keras models).
*   **`images/` (optional)**: Directory to store any images used in the project documentation (e.g., plots, visualizations).

## Installation and Dependencies

Before running the code, you need to install the required Python libraries. It is highly recommended to create a virtual environment to manage project dependencies.

**1. Create a virtual environment (recommended):**

   Using `venv` (Python 3.3+):
   ```bash
   python -m venv venv_project
   source venv_project/bin/activate  # On macOS/Linux
   venv_project\Scripts\activate      # On Windows
   **List of Required Libraries:**

   *   `pandas`
   *   `numpy`
   *   `scikit-learn` (scikit-learn)
   *   `matplotlib`
   *   `seaborn`
   *   `xgboost`
   *   `scikeras`
   *   `tensorflow`
