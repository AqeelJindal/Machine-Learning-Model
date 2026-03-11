# 3D BIOLOGICAL SHAPE ANALYSIS & PREDICTIVE MODELING
--------------------------------------------------

Applied machine learning pipeline in Python for the analysis of 3D biological structures 
using dimensionality reduction and regression techniques.

This project implements a comprehensive data science workflow to analyze the morphological 
characteristics of 3D blood vessel coordinates. By processing high-dimensional spatial data 
representing vessel shapes, the system identifies primary modes of structural variation and 
predicts shape attributes. The implementation features a robust Scikit-Learn pipeline 
integrating data imputation, feature scaling, and Linear Regression, with performance 
validated through RMSE metrics and spatial 3D visualizations.

## FEATURES
-----------

- **3D Morphological Analysis:** Processing and visualization of (x, y, z) coordinate data for complex biological shapes.
- **Dimensionality Reduction:** Implementation of Principal Component Analysis (PCA) to extract significant features and reduce noise from high-dimensional datasets.
- **Automated ML Pipelines:** End-to-end workflows using `sklearn.pipeline` to ensure reproducible data transformation and prevent data leakage during modeling.
- **Data Preprocessing:** Robust handling of missing values via `SimpleImputer` and feature normalization using `StandardScaler`.
- **Performance Analytics:** Comprehensive evaluation using Root Mean Squared Error (RMSE) and visual regression analysis (Actual vs. Predicted plots).

## TECHNOLOGIES
---------------

- **Language:** Python
- **Machine Learning:** Scikit-Learn (PCA, Pipelines, Linear Regression, Imputers)
- **Data Manipulation:** Pandas, NumPy
- **Visualization:** Matplotlib (including `mpl_toolkits.mplot3d` for 3D plotting)

## LEARNING OUTCOMES
--------------------

This project demonstrates practical understanding of:

- **Feature Engineering:** Managing high-dimensional spatial data and optimizing feature sets through PCA.
- **Pipeline Architecture:** Building scalable and professional-grade machine learning workflows.
- **Statistical Evaluation:** Interpreting regression metrics and identifying model generalization through train-test splitting.
- **Scientific Visualization:** Representing complex 3D structures and statistical results through clear, professional graphics.
