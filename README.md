# House Price Prediction Project

![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-FF9800?style=for-the-badge&logo=jupyter&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![EDA](https://img.shields.io/badge/EDA-4CAF50?style=for-the-badge)

**Kaggle Project:** [House Prices Competition](https://www.kaggle.com/code/mehdip1/house-prices-competition)  
**GitHub Repository:** [House Prices Project](https://github.com/Mehdipoladrag/House-Prices-Project)

## Project Overview
This project aims to predict house prices using the `train.csv` dataset and a separate test dataset. It demonstrates end-to-end data preprocessing, modeling, evaluation, and preparation of a submission file for Kaggle.

## Features of the Project
- **Data Analysis & Exploration:** 
  - Checked data structure, distributions, missing values, and duplicates.  
  - Visualized relationships between features and the target variable.  

- **Data Preprocessing:**  
  - Handled missing values (numeric columns filled, categorical columns filled with placeholders).  
  - Separated numerical and categorical features.  
  - Categorical features encoded using **One-Hot Encoding**.  

- **Models Implemented:**  
  - **Ridge Regression** (for comparison)  
  - **Random Forest Regression** (main model)  

- **Evaluation:**  
  - Model performance evaluated using training/test splits.  
  - Predictions made on a separate test dataset for more accurate assessment.  

- **Submission:**  
  - Generated `submission_rf.csv` containing `"Id"` and predicted `"SalePrice"` for Kaggle submission.  

## How to Run
1. Install required libraries (e.g., pandas, numpy, scikit-learn, matplotlib).  
2. Load the `train.csv` and test file.  
3. Run the preprocessing steps to handle missing values and encode categorical features.  
4. Train the Ridge and Random Forest models.  
5. Make predictions on the test dataset and generate the CSV submission file.  

## Notes
- Random Forest was chosen as the main model due to its superior predictive performance.  
- Linear regression and scaling steps were removed for simplicity and better results.  
- One-Hot Encoding ensures categorical features are properly represented numerically for machine learning models.
