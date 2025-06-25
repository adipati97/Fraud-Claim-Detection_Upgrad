# Insurance Fraud Detection Project

## Overview

This project aims to identify fraudulent insurance claims using machine learning techniques. By analyzing historical claim data, we build and evaluate models to help insurance companies efficiently detect and prevent fraud.

## Dataset

- Contains anonymized insurance claim records with customer, policy, incident, and claim details.
- Target variable: `fraud_reported` (Yes/No)

## Approach

1. **Data Preprocessing:**  
   - Removed identifiers and redundant columns  
   - Engineered new features (e.g., claim severity ratio)  
   - Encoded categorical variables  
   - Scaled numerical features

2. **Exploratory Data Analysis (EDA):**  
   - Visualized distributions and relationships  
   - Identified key predictors of fraud

3. **Modeling:**  
   - **Logistic Regression:** Interpretable, baseline model  
   - **Random Forest:** Nonlinear, high-performing model  
   - Performed feature selection, hyperparameter tuning, and threshold optimization

4. **Evaluation:**  
   - Compared models using accuracy, recall, specificity, and F1 score  
   - Assessed business trade-offs between detection rate and interpretability

## Results

- **Random Forest** achieved the highest recall and F1 score, making it the best choice for maximizing fraud detection.
- **Logistic Regression** is preferred when model transparency and interpretability are required.

## Usage

- Run the Jupyter notebook to reproduce the analysis.
- The final PDF report summarizes the workflow, results, and recommendations.

## Authors

- Dewang Shishodia
- Aditya Peesapati

## License

This project is for educational and demonstration purposes.
