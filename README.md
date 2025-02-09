# LendingClub-Credit-Scoring-Model-Project

## Overview
This project focuses on building a credit scorecard model using statistical techniques and machine learning. The primary objective is to analyze loan data, perform feature selection, and develop a logistic regression model to assess credit risk.

## Requirements
To run this project, ensure you have the following dependencies installed:

```bash
pip install pandas toad scikit-learn
```

## Data
The project uses multiple CSV files containing loan data from different quarters and years. These datasets are combined into a single DataFrame for analysis.

## Key Steps
1. **Data Loading**: The script reads multiple CSV files and combines them into a single dataset.
2. **Data Preprocessing**: Handles missing values, data cleaning, and transformation.
3. **Feature Selection**: Uses the `toad` package to perform feature selection for better model performance.
4. **Model Training**: Implements a logistic regression model using `scikit-learn`.
5. **Evaluation**: Assesses model performance using accuracy, ROC-AUC score, and classification reports.

## Usage
To run the project, execute the notebook `scorecard_commented.ipynb`. Ensure that all required datasets are in the same directory.

## Output
- The final logistic regression model for predicting creditworthiness.
- Performance metrics for evaluating model effectiveness.

## Contact
For any questions or improvements, feel free to reach out!

