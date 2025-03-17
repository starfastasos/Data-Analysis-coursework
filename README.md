# Data Analysis - Machine Learning Classification on Happiness Survey Data

## Table of Contents
1. [Project Description](#project-description)
2. [Dataset Information](#dataset-information)
3. [Installation Guide](#installation-guide)
4. [Usage Instructions](#usage-instructions)
   - [Data Preprocessing](#data-preprocessing)
   - [Classification Methods](#classification-methods)
   - [Model Evaluation](#model-evaluation)
   - [Model Optimization](#model-optimization)
5. [Additional Information](#additional-information)

## Project Description
This project focuses on **data classification** using various machine learning techniques. The goal is to predict a categorical target variable (`D`) based on multiple predictor variables (`X1, X2, ..., X6`). The analysis follows a structured approach:

1. **Data Preprocessing**: Cleaning and transforming the dataset.
2. **Classification Methods**: Applying different classification models.
3. **Model Evaluation**: Assessing model accuracy and performance.
4. **Model Optimization**: Fine-tuning models for better results.

## Dataset Information
- **Dataset Used**: `SomervilleHappinessSurvey2015.csv`
- **File Format**: CSV (Tab-delimited, UTF-16 encoding)
- **Features**: 
  - Predictor variables: `X1, X2, X3, X4, X5, X6`
  - Target variable: `D` (Categorical)

## Installation Guide
### Prerequisites:
- **Python 3.x**
- Required libraries:
  ```sh
  pip install pandas scikit-learn matplotlib seaborn
  ```

## Usage Instructions

### Data Preprocessing
- Load the dataset using Pandas.
- Check data types and handle missing values.

### Classification Methods
- Implement multiple classification algorithms.
- Train models using scikit-learn.

### Model Evaluation
- Compare performance using accuracy scores and confusion matrices.

### Model Optimization
- Apply techniques such as hyperparameter tuning.

## Additional Information
For detailed analysis steps and code, refer to the Jupyter Notebook (`Data_Analysis.ipynb`).
