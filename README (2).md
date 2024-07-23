#Loan Approval Prediction

This project aims to predict whether a loan application will be approved based on various factors. It uses a Support Vector Machine (SVM) model for the classification task. The dataset used in this project contains information about loan applicants, including their personal details and loan-related information.

## Table of Contents

- [Installation](#installation)
- [Dependencies](#dependencies)
- [Data Collection and Processing](#data-collection-and-processing)
- [Data Visualization](#data-visualization)
- [Model Training](#model-training)
- [Model Evaluation](#model-evaluation)





## Dependencies

Make sure you have the following Python packages installed:
- numpy
- pandas
- seaborn
- scikit-learn



## Data Collection and Processing

1. **Loading the Dataset**: The dataset is loaded into a pandas DataFrame from a CSV file.
2. **Data Exploration**:
   - Print the first five rows of the dataframe.
   - Check the number of rows and columns.
   - Generate statistical measures.
   - Check for missing values.
3. **Data Cleaning**:
   - Drop rows with missing values.
   - Encode categorical variables into numerical values.
   - Replace values in the 'Dependents' column.
4. **Label Encoding**: Encode the target variable 'Loan_Status'.

## Data Visualization

Use seaborn to create count plots to visualize the relationship between:
- Education and Loan Status
- Marital Status and Loan Status

## Model Training

1. **Train-Test Split**:
   - Split the data into training and testing sets with a test size of 10% and stratification on the target variable.
2. **Training the Model**:
   - Use the Support Vector Machine (SVM) classifier with a linear kernel to train the model.

## Model Evaluation

Evaluate the model's performance using accuracy score:
- On the training data
- On the test data



