# Predicting Metal Component Lifespan – Machine Learning Project

This project is part of the MSc Data Science program coursework at the University of Greenwich. The objective is to apply regression and classification machine learning techniques to predict the lifespan and classify the durability of metal components based on their properties and production parameters.

## Problem Statement

To reduce defect rates and improve production efficiency, we built models to:
- Predict the lifespan (in hours) of metal parts (regression)
- Classify whether parts are durable or not based on a 1500-hour threshold (classification)

## Techniques Used

### Regression Models
- Random Forest Regressor
- XGBoost Regressor

### Classification Models
- Random Forest Classifier
- Support Vector Machine (SVM)

## Key Methods

- Data Preprocessing: Feature encoding, scaling, train-test split
- EDA: Correlation matrix, histogram, PCA for clustering
- Hyperparameter Tuning: GridSearchCV & Bayesian optimization
- Model Evaluation: MSE, RMSE, R² for regression; Accuracy, AUC, F1-score for classification

## ✅ Results

| Task         | Best Model       | Key Metric | Score      |
|--------------|------------------|------------|------------|
| Regression   | Random Forest    | RMSE       | Low error  |
| Classification | SVM           | Accuracy   | 99.7%      |

SVM was the most accurate and reliable model for classifying parts as durable or defective, making it the recommended choice for deployment.

## Files

- `Metal-component-lifespan.ipynb`: Full implementation notebook
- `metal-component-lifespan-prediction_Report.pdf`: Formal report
- `README.md`: Project summary 

## Future Improvements

- Integrate gradient boosting classification (e.g., LightGBM)
- Use PCA for dimensionality reduction before modeling
- Automate model selection in pipeline format

## Contact

For questions, please reach out at: **kruthibhaskarmys@gmail.com**
