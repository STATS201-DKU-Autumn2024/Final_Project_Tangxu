# Enhancing Predictive Maintenance for Turbofan Engines

This repository focuses on developing a predictive maintenance model for turbofan engines using the NASA Turbofan Engine Degradation Simulation Dataset. By leveraging advanced machine learning techniques, particularly Long Short-Term Memory (LSTM) networks, the project aims to predict the Remaining Useful Life (RUL) of engines based on sensor data, enabling proactive maintenance strategies and minimizing unexpected failures.

---

## Project Overview

The project is centered on predictive maintenance for high-performance turbofan engines. The NASA dataset provides multivariate time-series data from simulated engines, capturing operational metrics and degradation over time. The goal is to develop a model capable of accurately predicting the RUL for engines under various operational conditions.

Key highlights of the project include:
- **Data Preprocessing**: Cleaning, normalizing, and preparing time-series data for model training.
- **LSTM Model Development**: Building and training a deep learning model to capture temporal dependencies in the data.
- **Model Evaluation**: Assessing the model's performance using metrics like Root Mean Squared Error (RMSE) and visualizing prediction accuracy.

---

## Notebook File Explanation

The notebook file `Enhancing_Predictive_Maintenance_for_Turbofan_Engines.ipynb` includes the following sections:
1. **Introduction**: An overview of the project and dataset details.
2. **Data Preprocessing**: Steps for data cleaning, normalization, and preparation for input into the LSTM model.
3. **Model Building**: Construction of the LSTM model, including hyperparameter selection and configuration.
4. **Training and Validation**: Training the model on the dataset and validating its performance.
5. **Visualization**: Generating plots to compare predicted RUL values with actual values, including insights into model accuracy.
6. **Model Evaluation**: Using RMSE and other evaluation metrics to assess the predictive capability of the model.

You can access the notebook on Google Colab via the following link:  
[Colab Notebook: Enhancing Predictive Maintenance for Turbofan Engines](https://colab.research.google.com/drive/1DL0-iba6HReCSmTpzFwX3IJCCE68inaf#scrollTo=W_mD1ptTbSNs)

---

## Prerequisites

The environment requirements for running this project can be accessed from the main page: [Environment Requirements](https://github.com/STATS201-DKU-Autumn2024/Final_Project_Tangxu/tree/main).

Ensure all dependencies listed in the `requirements.txt` file are installed before running the notebook.

---

## Usage Instructions

The primary code for this analysis is contained in the Jupyter Notebook file **Enhancing_Predictive_Maintenance_for_Turbofan_Engines.ipynb**. This notebook is designed to be executed in Google Colab, providing an interactive environment where users can modify parameters and observe real-time results of the predictive maintenance models.

### Download the Dataset

1. Download the **NASA Turbofan Engine Degradation Simulation Dataset** from the [project data folder](https://github.com/STATS201-DKU-Autumn2024/Final_Project_Tangxu/tree/main/Data).
2. Upload the downloaded data files to your Google Colab environment for seamless access.

### Running the Notebook

1. Open the **Enhancing_Predictive_Maintenance_for_Turbofan_Engines.ipynb** file directly in Google Colab by using the following link:  
   [Open in Colab](https://colab.research.google.com/drive/1DL0-iba6HReCSmTpzFwX3IJCCE68inaf#scrollTo=W_mD1ptTbSNs).
2. Ensure that all required libraries (e.g., `pandas`, `numpy`, `matplotlib`, `scikit-learn`, `tensorflow`) are installed within the Colab environment. Most dependencies are pre-installed in Colab.
3. Upload the dataset files to your Colab environment using the file upload utility.
4. Execute each cell in the notebook sequentially to perform data preprocessing, model training, visualization, and evaluation for predictive maintenance tasks.
