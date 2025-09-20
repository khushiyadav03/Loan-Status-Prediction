# Loan Eligibility Prediction

This project focuses on building a machine learning model to predict loan eligibility based on various factors.

## Dataset

The project uses the `loan_dataset.csv` which contains information about loan applicants, including their personal details, income, loan amount, credit history, and loan status.

## Project Steps

1.  **Data Loading and Exploration**: Load the dataset and perform initial exploration to understand its structure, check for missing values, and get descriptive statistics.
2.  **Data Preprocessing**: Handle missing values by dropping rows with nulls. Convert categorical features into numerical representations using one-hot encoding or label encoding as appropriate. The 'Loan_Status' column is also converted to numerical labels (0 for 'N', 1 for 'Y'). The 'Dependents' column's '3+' value is replaced with '4'.
3.  **Data Visualization**: Visualize the relationship between key features like 'Education' and 'Married' with the 'Loan_Status' to gain insights into the data.
4.  **Model Training**: Split the data into training and testing sets. A Support Vector Machine (SVM) model with a linear kernel is trained on the training data.
5.  **Model Evaluation**: Evaluate the trained model's performance using accuracy scores on both the training and testing datasets.
6.  **Predictive System**: Implement a system to take user input for the relevant features and predict the loan eligibility using the trained SVM model.

## Model Performance

-   Training Data Accuracy: [Insert Training Accuracy Score Here]
-   Testing Data Accuracy: [Insert Testing Accuracy Score Here]

## How to Use

1.  Clone the repository.
2.  Ensure you have the necessary libraries installed (pandas, numpy, seaborn, scikit-learn).
3.  Run the Jupyter Notebook or Python script.
4.  Use the predictive system section to get loan eligibility predictions by providing the required input.

## Future Improvements

- Explore other machine learning algorithms (e.g., Logistic Regression, Random Forest) to compare performance.
- Perform more extensive feature engineering.
- Address the imbalanced nature of the target variable, if any.
- Implement cross-validation for more robust model evaluation.
