#Predicting NBA Player Performance with PCA, LDA, and Logistic Regression Pipeline

## Overview
This project focuses on predicting NBA player performance using machine learning techniques, specifically logistic regression models trained on data preprocessed with dimensionality reduction techniques such as PCA (Principal Component Analysis) and LDA (Linear Discriminant Analysis). The goal is to build a pipeline that accurately predicts whether a player will perform well based on various attributes and statistics.

## Dataset
The dataset used in this project is sourced from [provide source if available]. It contains data on NBA players, including their performance statistics, demographics, and other relevant features. The dataset has been preprocessed to handle missing values, encode categorical variables, and remove irrelevant columns.

## Dependencies
To run the code in this project, you will need the following dependencies:
- Python (version X.X.X)
- pandas
- scikit-learn
- matplotlib (optional, for visualization)

## Usage
1. **Data Preprocessing**: The dataset is loaded and preprocessed using pandas. Missing values are handled, irrelevant columns are dropped, and the target variable is encoded.
2. **Logistic Regression Model**: A logistic regression model is trained on the original dataset to establish a baseline performance.
3. **PCA (Principal Component Analysis)**: The data is standardized and transformed using PCA to reduce dimensionality while retaining most of the variance.
4. **LDA (Linear Discriminant Analysis)**: Similar to PCA, LDA is applied to reduce dimensionality and improve separability between classes.
5. **Training Models with Reduced Dimensions**: Logistic regression models are trained on the transformed data obtained from PCA and LDA.
6. **Evaluation**: Classification reports are generated to evaluate the performance of each model, comparing accuracy, precision, recall, and F1-score.

## Files
- **nba_final.csv**: The dataset used in the project.
- **main.ipynb**: Jupyter Notebook containing the code for data preprocessing, model training, and evaluation.
- **README.md**: This file, providing an overview of the project, usage instructions, and dependencies.

## Results
The project achieves promising results in predicting NBA player performance. By leveraging dimensionality reduction techniques such as PCA and LDA, we were able to improve the model's performance compared to the baseline logistic regression model trained on the original dataset.

## Contributors
- Anurag Slathia


