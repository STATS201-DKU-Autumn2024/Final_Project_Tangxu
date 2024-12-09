# Enhancing Predictive Maintenance for Turbofan Engines

This repository focuses on developing predictive maintenance models for turbofan engines using the NASA Turbofan Engine Degradation Simulation Dataset. By leveraging advanced machine learning techniques, particularly Long Short-Term Memory (LSTM) networks and Temporal Convolutional Networks (TCNs), the project aims to predict the Remaining Useful Life (RUL) of engines based on sensor data, enabling proactive maintenance strategies and minimizing unexpected failures.

---

## Project Overview

The project is centered on predictive maintenance for high-performance turbofan engines. The NASA dataset provides multivariate time-series data from simulated engines, capturing operational metrics and degradation over time. The goal is to develop models capable of accurately predicting the RUL for engines under various operational conditions.

Key highlights of the project include:
- **Data Preprocessing**: Cleaning, normalizing, and preparing time-series data for model training.
- **Model Development**:
  - **LSTM Models**: Capture temporal dependencies in the data.
  - **TCN Models**: Leverage dilated convolutions to capture both short- and long-term dependencies efficiently.
- **Model Evaluation**: Assessing performance using metrics like Root Mean Squared Error (RMSE) and visualizing prediction accuracy.
- **Explainability**: Utilizing SHAP (SHapley Additive exPlanations) to interpret the significance of individual features.

---

## Notebook File Explanation

### Notebook 1: LSTM-Based Predictive Maintenance
The notebook file `Enhancing_Predictive_Maintenance_for_Turbofan_Engines.ipynb` includes the following sections:
1. **Introduction**: An overview of the project and dataset details.
2. **Data Preprocessing**: Steps for data cleaning, normalization, and preparation for input into the LSTM model.
3. **Model Building**: Construction of the LSTM model, including hyperparameter selection and configuration.
4. **Training and Validation**: Training the model on the dataset and validating its performance.
5. **Visualization**: Generating plots to compare predicted RUL values with actual values, including insights into model accuracy.
6. **Model Evaluation**: Using RMSE and other evaluation metrics to assess the predictive capability of the model.

You can access this notebook on Google Colab via the following link:  
[Colab Notebook 1: LSTM-Based Predictive Maintenance](https://colab.research.google.com/drive/1jcLABjjTRogIBM1XDIZbh4oTrAxyuKBp)

### Notebook 2: TCN and SHAP-Based Predictive Maintenance
The notebook file `TCN_and_Visualization_using_SHAP.ipynb` includes the following sections:
1. **Introduction**: Explanation of the TCN model and its advantages for time-series analysis.
2. **Data Preprocessing**: Detailed steps for cleaning and preparing the dataset for TCN models.
3. **Model Building**: Construction and training of the TCN model, including hyperparameter tuning and optimization.
4. **SHAP Analysis**: Visualization of feature contributions to the model predictions using SHAP summary and force plots.
5. **Comparative Analysis**: Comparing TCN performance with traditional models like Random Forest and SVM.

You can access this notebook on Google Colab via the following link:  
[Colab Notebook 2: TCN and SHAP-Based Predictive Maintenance](https://colab.research.google.com/drive/1_uNJm4qtow-2Esn_ZCvqRnrXpzeZ2Lc1#scrollTo=x_NrR6PfzNpH)

---

## Prerequisites

The environment requirements for running this project can be accessed from the main page: [Environment Requirements](https://github.com/STATS201-DKU-Autumn2024/Final_Project_Tangxu/tree/main/Docs/Dependencies).

Ensure all dependencies listed in the `installed_packages.txt` file are installed before running the notebooks. Most required libraries, including `pandas`, `numpy`, `matplotlib`, `scikit-learn`, and `tensorflow`, are pre-installed in Google Colab.

---

## Usage Instructions

The primary code for this analysis is contained in two Jupyter Notebook files, which can be executed in Google Colab for an interactive experience.

### Download the Dataset

1. Download the **NASA Turbofan Engine Degradation Simulation Dataset** from the [project data folder](https://github.com/STATS201-DKU-Autumn2024/Final_Project_Tangxu/tree/main/Data).
2. Upload the downloaded data files to your Google Colab environment for seamless access.

### Running the LSTM-Based Notebook

1. Open the **Enhancing_Predictive_Maintenance_for_Turbofan_Engines.ipynb** file directly in Google Colab by using the following link:  
   [Open Colab Notebook 1](https://colab.research.google.com/drive/1DL0-iba6HReCSmTpzFwX3IJCCE68inaf#scrollTo=W_mD1ptTbSNs)
2. Upload the dataset files to your Colab environment using the file upload utility.
3. Execute each cell sequentially to preprocess the data, train the LSTM model, and evaluate its performance.

### Running the TCN and SHAP-Based Notebook

1. Open the **TCN_and_Visualization_using_SHAP.ipynb** file directly in Google Colab by using the following link:  
   [Open Colab Notebook 2](https://colab.research.google.com/drive/1_uNJm4qtow-2Esn_ZCvqRnrXpzeZ2Lc1#scrollTo=x_NrR6PfzNpH)
2. Upload the dataset files to your Colab environment using the file upload utility.
3. Execute each cell sequentially to train the TCN model, evaluate its performance, and visualize feature contributions using SHAP.

---

By utilizing these notebooks, users can explore and compare LSTM and TCN models, gaining insights into predictive maintenance strategies for turbofan engines.
