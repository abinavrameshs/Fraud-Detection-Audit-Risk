# Fraud-Detection-Audit-Risk
Fraud Detection on Audit Risk Dataset

# Aim 
Build a Classification model to predict `Risk` of a firm, given various Risk factors

The dataset used is present in the repository. A small description of the features are provided in the screenshot capture.

# Steps performed 
1. Import Packages
2. Key Takeaways for Business
3. Profiling report and Correlations
    - Pandas profiling report
    - Phik (φk) correlations
4. Exploratory Data Analysis (EDA)
    - Sector score vs Risk
    - LOCATION_ID vs Risk
    - PARA_A vs Risk
    - PARA_B vs Risk
    - Numbers vs Risk
    - Money_Value vs Risk
    - District_Loss vs Risk
    - History vs Risk
    - Score vs Risk
5. Classification Model to predict Fraud
    - Pre-Processing
    - Setting up the Pre-processing pipeline
    - Modelling for Fraud
        - Building top 10 models
        - Tuning Hyperparameters of top 10 models
    - Feature importances
    - AUC Plot
    - Confusion Matrix
    - Using SHAP values to explain the model
    

# Modelling Procedure  
Used PyCaret to perform Pre-processing pipeline and for building a Classification model to predict `Risk`. 
Many models were implemented, tuned and 1 Champion model was selected.


