# Customer Churn Prediction Using Machine Learning

## Project Overview
This project focuses on predicting customer churn using Machine Learning classification techniques.

The goal is to identify customers who are likely to leave a service, helping businesses understand customer behavior and improve customer retention strategies.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib


## Machine Learning Workflow
1. Data Loading and Exploration
2. Data Cleaning and Preprocessing
3. Handling Missing Values
4. Feature Engineering and Encoding
5. Logistic Regression Model Training
6. Stratified Cross-Validation
7. Model Evaluation
8. Decision Threshold Analysis

## Model Performance

The final Logistic Regression model achieved the following results on the test dataset:

| Metric | No | Yes |
|---|---:|---:|
| Precision | 0.90 | 0.50 |
| Recall | 0.72 | 0.78 |
| F1-Score | 0.80 | 0.61 |
| Support | 1035 | 374 |

**Overall Accuracy: 74%**

### Key Findings
- The model achieved 78% Recall for the Churn (Yes) class.
- The model identified a significant proportion of customers likely to leave.
- Precision and Recall were evaluated to understand the trade-off between detecting churn and false positive predictions.

## Project Structure

- `Customer_Churn_Prediction.ipynb` – Main Jupyter Notebook containing the complete machine learning workflow.
- `README.md` – Project documentation.

## Conclusion

This project demonstrates a practical application of Machine Learning in customer behavior analysis and churn prediction.

It provided hands-on experience in data preprocessing, classification, model evaluation, cross-validation, and decision threshold analysis.

## Author
Samer Aldenas

Artificial Intelligence Student | Aspiring Machine Learning Engineer
