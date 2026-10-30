# Feature Engineering & Preprocessing Pipeline

## Project Overview
This project demonstrates a machine learning preprocessing pipeline using Python and Scikit-Learn. It handles missing values, scales numerical features, encodes categorical features, analyzes correlations, and identifies important features.

## Objectives
- Handle missing values using imputation.
- Scale numerical features using StandardScaler.
- Encode categorical features using One-Hot Encoding.
- Prevent data leakage by splitting data before fitting transformations.
- Analyze feature correlations.
- Identify important features using Mutual Information and Random Forest.
- Evaluate the machine learning model.

## Dataset
The project uses a synthetic customer churn dataset containing customer details, monthly spending, support tickets, contract types, and churn status.

**Note:** The included dataset is synthetic and intended for demonstrating the preprocessing workflow.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- Google Colab

## Preprocessing Pipeline
1. Load and explore the dataset.
2. Check for missing values.
3. Split the dataset into training and testing sets.
4. Impute missing numerical values using the median.
5. Scale numerical features using StandardScaler.
6. Impute missing categorical values using the most frequent value.
7. Apply One-Hot Encoding to categorical features.
8. Combine preprocessing and model training using Pipeline and ColumnTransformer.
9. Analyze correlations and feature importance.
10. Evaluate model performance on the test dataset.

## Files Included
- `feature_engineering_preprocessing_pipeline.ipynb` — Jupyter Notebook containing the implementation.
- `customer_risk_synthetic.csv` — Dataset used for the project.
- `README.md` — Project documentation.

## How to Run
1. Open the notebook in Google Colab.
2. Run the notebook cells in order.
3. Upload the CSV dataset when prompted.
4. Review the preprocessing steps, feature analysis, and evaluation results.

## Conclusion
This project demonstrates a reusable machine learning preprocessing workflow designed to improve data quality, prepare features for modeling, and reduce data leakage.
