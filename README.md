# Heart Transplantation Waiting Time Prediction

This project aims to develop a binary classification model for predicting heart transplantation (HT) waiting times for patients. The accurate prediction of waiting times can have significant benefits for both hospitals and patients themselves. In addition, this project aims to identify predictive patient factors that tend to shorten or lengthen waiting times.

## Abstract

Predicting heart transplantation (HT) waiting times for patients is difficult and can have great benefits for hospitals and the patients themselves. This project addresses these challenges by developing a binary classification model to predict whether a patient will experience a longer or shorter waiting time than the computed median time of 88 days in queue for a heart transplantation based on the UNOS database. Different regression models and neural network architectures were evaluated to achieve this goal. The best performing logistic regression (log) architecture reached an F1 score of 69.8%, while the neural network achieved an F1 score of 71.3%.

## Key Features

- Binary classification model for heart transplantation waiting time prediction.
- Evaluation of different regression models and neural network architectures.
- Identification of predictive patient factors influencing waiting times.
- Comparison of logistic regression and neural network performance.
- Achieved F1 scores of 69.8% for logistic regression and 71.3% for the neural network.

## Dataset

The heart transplantation waiting time prediction model is based on data from the UNOS database. The dataset includes relevant patient information such as medical history and diagnostic details.

## Methodology

1. Data preprocessing: The dataset was cleaned and preprocessed to handle missing values, outliers, and categorical variables.

2. Feature selection: Relevant features that could potentially impact waiting times were identified through exploratory data analysis, a feature selection algorithm (RFECV) and domain knowledge.

3. Model selection and evaluation: Different regression models and neural network architectures were trained and evaluated using appropriate performance metrics such as F1 score.

4. Logistic regression: A logistic regression model was trained to classify patients into two categories: longer or shorter waiting time compared to the median time.

5. Neural network architecture: A neural network model was designed and trained to perform binary classification on the dataset.

6. Model comparison: The performance of the logistic regression and neural network models was compared to determine the best performing approach.

## Results

The logistic regression model achieved an F1 score of 69.8%, indicating its ability to accurately classify patients based on waiting time. The neural network architecture performed slightly better, with an F1 score of 71.3%.
