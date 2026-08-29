# Loan Status Prediction Using Machine Learning

## Project Overview

This project uses Machine Learning to predict whether a loan application is likely to be approved or not based on the applicant's information.

The project uses a classification approach to predict the loan status.

## Dataset

The dataset contains **614 records** and **13 columns**.

The dataset includes information related to loan applicants, such as:

- Gender
- Married
- Dependents
- Education
- Self Employed
- Applicant Income
- Coapplicant Income
- Loan Amount
- Loan Amount Term
- Credit History
- Property Area
- Loan Status

The target variable is `Loan_Status`.

## Technologies Used

- Python
- NumPy
- Pandas
- Seaborn
- Scikit-learn
- Google Colab

## Methodology

The project follows these steps:

1. Import the required Python libraries.
2. Load the loan dataset.
3. Explore and analyze the dataset.
4. Check and handle missing values.
5. Convert categorical data into suitable numerical form.
6. Separate the features and target variable.
7. Split the dataset into training and testing data.
8. Train the machine learning classification model.
9. Evaluate the model using accuracy score.
10. Use the trained model for loan status prediction.

## Machine Learning Model

A Support Vector Machine (SVM) classification model is used for predicting the loan status.

The dataset is divided into training and testing data for model evaluation.

## Dataset File

The dataset used in this project is:

`loan.csv`

## Files in This Repository

- `Loan_Status_Prediction.ipynb` – Project Jupyter Notebook
- `loan.csv` – Dataset used for the project
- Project PowerPoint Presentation – Project explanation and results
- `README.md` – Project documentation

## Conclusion

This project demonstrates how Machine Learning can be used to predict loan approval status based on applicant information.

The project includes data preprocessing, model training, evaluation, and prediction using a classification approach.
