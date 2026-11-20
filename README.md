# INVESTIGATING-TRANSPORT-ACCESSIBILITY-INEQUALITIES-IN-ENGLAND-DURING-THE-2022-2023-UK-ENERGY-CRISIS
This is the repository for my Dissertation Project

The 2022–2023 UK energy crisis, characterised by substantial increase. This study investigates spatial inequalities in transport accessibility across England and applies explainable machine learning to identify the factors associated with accessibility disadvantage.

1. First Access DFT datasets and run the jupyter notebooks
2. Then Run Harmonised Notebook in Harmonised DFT Datasets
3. Then Run Notebooks in ONS Datasets
4. Then Run Notebooks in Energy Datasets
5. Then finally run the Master Notebook where Integrated Dataset is formed, feature engineering is done to build new useful features for target construction.
6. Target Variable is Accessibility Inequality Metric
7. This is Followed my Predictive Modelling using Linear Regression as baseline, followed by Random Forest and Gradient Boosting. 16 Predictors are extracted among the 43 features from Master dataframe
8. Model Evaluation and Cross-Validation is performed to find the best suitable model
9. Selected Model will be used finally for Explainable AI using SHAP analysis
Here which predictor played a major role in the performance of the model will be figured out and how much each of the predictors influenced to get the final Output(AIM score)
