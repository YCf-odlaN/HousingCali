# HousingCali
California Housing Prices Prediction

Predict median housing prices in California districts using machine learning.
Based on Chapter 2 of "Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow" by Aurélien Géron.

Project Summary

    Goal: Build a model to predict median housing prices using 1990 California census data.

    Key Steps:

        Data Exploration: Analyzed correlations, visualized geographical patterns, and engineered new features (e.g., rooms_per_house).

        Preprocessing: Handled missing values, scaled features, and encoded categorical variables (e.g., ocean_proximity).

        Model Training: Evaluated Linear Regression, Decision Trees, and Random Forests.

        Best Model: Random Forest Regressor achieved a test RMSE of ~$41,424.

Quick Start
Run the Project

    Download the Data:
    python
    Copy

    # Code included in the notebook automatically downloads the dataset:
    from pathlib import Path
    import pandas as pd
    import tarfile
    import urllib.request

    def load_housing_data():
        # ... (see notebook for full code)

    Run the Notebook:
    Open in Google Colab
    or
    bash
    Copy

    jupyter notebook notebooks/end_to_end_ml_project.ipynb

Key Findings

    Top Predictor: median_income had the strongest correlation with housing prices.

    Geographical Clusters: Proximity to the ocean and latitude/longitude clusters improved predictions.

    Model Comparison:
    Model	Validation RMSE
    Linear Regression	~$68,687
    Decision Tree	~$66,868
    Random Forest	~$41,424


License

This project is licensed under the MIT License. See LICENSE for details.
Acknowledgements

    Dataset sourced from Aurélien Géron’s GitHub.

    Inspired by Chapter 2 of Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow.
