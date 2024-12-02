# Visualization Directory for Predictive Maintenance Project

This directory contains visualizations generated as part of the predictive maintenance project for turbofan engines. The visualizations provide insights into model performance, data trends, and feature contributions, aiding in the interpretation of the results and the effectiveness of the implemented models.

---

## Contents

### 1. **SHAP Visualizations**
   - **File:** `SHAP.png`
   - **Description:** This visualization demonstrates the feature contributions to the Temporal Convolutional Network (TCN) model's predictions using SHapley Additive exPlanations (SHAP). 
   - **Insights:**
     - Highlights the importance of specific sensor measurements in predicting Remaining Useful Life (RUL).
     - Includes a scatter plot where feature values are represented by color intensity, providing interpretability for the TCN model.

### 2. **Time-Series Analysis**
   - **File:** `Time-Series Analysis.png`
   - **Description:** This visualization illustrates the time-series trends of selected sensor measurements for a sample engine unit in the dataset.
   - **Insights:**
     - Helps identify patterns and relationships between sensor readings over the operational cycles.
     - Facilitates understanding of how sensor data reflects engine degradation over time.

### 3. **RUL Predictions**
   - **File:** `RUL.png`
   - **Description:** A plot comparing the true RUL values against the predicted RUL values from the implemented LSTM model.
   - **Insights:**
     - Evaluates the accuracy of the predictive models.
     - Highlights areas where model predictions deviate from actual RUL values, indicating potential improvement opportunities.

### 4. **Correlation Heatmap**
   - **File:** `Heatmap.png`
   - **Description:** A heatmap visualizing correlations between sensor measurements.
   - **Insights:**
     - Identifies strong relationships between features, providing clues for feature engineering and model optimization.
     - Highlights multicollinearity or redundant information, aiding in feature selection.

---

## Purpose of Visualizations

The visualizations in this directory are designed to:
- Provide interpretability for machine learning models by analyzing feature contributions using SHAP.
- Illustrate the temporal dynamics of sensor readings to understand degradation trends.
- Evaluate and compare model predictions to validate performance.
- Highlight correlations between features for better feature engineering and model refinement.

---

## How to Use

1. **Access the Visualizations:**
   Open the `.png` files in this directory to view the visualizations. Each file is named to indicate the type of analysis or insight provided.

2. **Incorporate into Reports:**
   Use these visualizations in project reports or presentations to support findings and illustrate key concepts.

3. **Recreate the Visualizations:**
   Run the relevant Jupyter notebooks in the repository to generate these visualizations. For example:
   - SHAP visualizations can be recreated in the `TCN_and_Visualization_using_SHAP.ipynb` notebook.
   - Time-series plots, RUL predictions, and heatmaps can be generated in both `Enhancing_Predictive_Maintenance_for_Turbofan_Engines.ipynb` and `TCN_and_Visualization_using_SHAP.ipynb`.

---

## Relevant Notebooks

- **LSTM-Based Predictive Maintenance Notebook:**  
  [Colab Notebook 1](https://colab.research.google.com/drive/1DL0-iba6HReCSmTpzFwX3IJCCE68inaf#scrollTo=W_mD1ptTbSNs)

- **TCN and SHAP-Based Predictive Maintenance Notebook:**  
  [Colab Notebook 2](https://colab.research.google.com/drive/1_uNJm4qtow-2Esn_ZCvqRnrXpzeZ2Lc1#scrollTo=x_NrR6PfzNpH)

---

These visualizations are essential for understanding the performance and behavior of predictive maintenance models, exploring feature relationships, and supporting actionable decision-making in engineering applications.
