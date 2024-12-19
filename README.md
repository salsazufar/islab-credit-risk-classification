# Credit Risk Classification Using Machine Learning

This project involves developing a machine learning pipeline to classify individuals as high or low credit risk using the German Credit Dataset (`dataset_31_credit-g.arff`). It includes extensive exploratory data analysis (EDA), feature engineering, and model experimentation to identify the best-performing model.

## Features
- **Exploratory Data Analysis (EDA):** Gained insights into the dataset, including data distributions and correlations.
- **Feature Engineering:** Handled missing values, encoded categorical variables, and normalized numerical features.
- **Model Experimentation:** Tested multiple models (Logistic Regression, Decision Tree, XGBoost, SVM) with hyperparameter tuning.
- **Performance Metrics:** Evaluated models using Accuracy, Precision, Recall, F1 Score, and ROC-AUC.
- **Best Model:** Achieved a ROC-AUC of 0.910 with XGBoost.

## Requirements
Install the dependencies using the command:
```bash
pip install -r requirements.txt
```

## Usage
1. Clone this repository and navigate to the project directory.
2. Ensure the dataset (`dataset_31_credit-g.arff`) is available in the working directory.
3. Run the Jupyter Notebook to execute the pipeline step by step.

## Key Results
- XGBoost emerged as the best-performing model, demonstrating superior classification capabilities.
- Logistic Regression was identified as a simpler yet effective alternative.

## Tools and Technologies
- Python, Scikit-learn, XGBoost, Pandas, Matplotlib
- Jupyter Notebook for an interactive and iterative workflow.

## Acknowledgements
This project was developed using the German Credit Dataset from the UCI Machine Learning Repository.
