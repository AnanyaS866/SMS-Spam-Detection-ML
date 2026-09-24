# SMS Spam Detection Using Machine Learning

## Project Overview

This project uses machine learning to classify SMS messages as Spam or Not Spam.

## Objective

The main objective is to build and evaluate supervised machine learning classification models for detecting spam SMS messages.

## Dataset

The project uses the SMS Spam Collection dataset from the UCI Machine Learning Repository.

The dataset contains SMS messages labeled as:
- Ham (Not Spam)
- Spam

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Machine Learning Algorithms

Two classification algorithms were compared:

1. Logistic Regression
2. Random Forest

## Data Preprocessing

The following preprocessing steps were performed:

- Checked for missing values
- Removed duplicate records
- Converted labels into numerical values
- Split the dataset into training and testing sets
- Used TF-IDF to convert text messages into numerical features

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- 5-Fold Cross-Validation

## Results

| Model | Accuracy | Precision | Recall | F1 Score | ROC-AUC | CV Accuracy |
|---|---:|---:|---:|---:|---:|---:|
| Logistic Regression | 96.42% | 96.08% | 74.81% | 84.12% | 98.74% | 95.16% |
| Random Forest | 97.10% | 99.03% | 77.86% | 87.18% | 99.02% | 97.03% |

## Conclusion

The project demonstrates that machine learning can be effectively used for SMS spam detection. Both models achieved strong performance, with Random Forest producing higher scores on the reported test and cross-validation metrics.

## Notebook

The complete project notebook is available in this repository:

`SMS_Spam_Detection_ML_Project.ipynb`
