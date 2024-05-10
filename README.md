# Credit Score Prediction

## Description
This repository contains the work for a project focused on analyzing and predicting credit scores using machine learning models. The project aims to provide insights into credit score data and build predictive models that can help determine the likelihood of credit card approval.

## Table of Contents
- [Installation](#installation)
- [File Descriptions](#file-descriptions)
- [Usage](#usage)
- [Contributors](#contributing)

## Installation
To set up this project locally, follow these steps:
```bash
git clone git@github.com:SimonSaysGiveMeSmile/Caffeinated-Treasury-Bot-ORIE-4741-.git
```

## File Descriptions
**data_cleaning.ipynb**: Notebook for preprocessing and cleaning the dataset.

**data_analysis_v1.ipynb**: Initial draft analyzing and predicting credit scores using basic machine learning models.

**data_analysis_v2.ipynb**: Improved version including model evaluations and enhancements.

**data_analysis_v3.ipynb**: Comprehensive analysis with additional machine learning models and stacking techniques. This is the final version for detailed insights.

**Model_Predictions.ipynb**: Interactive dashboard for users to predict credit card approval based on trained models.

**CAT_Model.pkl, LOG_Model.pkl, RF_Model.pkl, SVM_Model.pkl**: Serialized files for trained models CatBoost, Logistic Regression, Random Forest, and SVM respectively.


**All_Model.pkl**: a trained model that combines the result of Logistic Regression, Random Forest, and SVM respectively.

**test.csv, test_cleaned.csv, train.csv, train_cleaned.csv**: Data files used in the project, including both raw and cleaned versions.

## Usage
To run the main analysis:
```bash
jupyter notebook data_analysis_v3.ipynb
```

To use the prediction dashboard:
```bash
jupyter notebook Model_Predictions.ipynb
```

### Contributors
Simon Tian, Cecilia Yang, Kayla Yang


