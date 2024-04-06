# Project Intro/Objective

The project consists of a historical dataset on the modern Olympic Games, including all the Games from Athens 1896 to Rio 2016. The objective of it is to predict wether an athlete will win a medal or not. 

The dataset is obtained from the Kaggle website: '120 years of Olympic history: athletes and results' - https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results



# Methods Used

- Logistic Regression

- PyCaret

- Neural Network



# Technologies

- Python 

- Deep Learning (Keras TensorFlow)



# Project Description

This project aimed to develop a predictive model for a classification task using machine learning techniques. Below is an outline of the steps taken during the project:

- Baseline Model: We initially executed a Logistic Regression model to establish a performance baseline.

- Data Exploration and Feature Engineering: We conducted thorough data exploration and performed feature engineering to enhance the predictive power of the model. This involved creating new variables from existing columns and addressing missing values in numeric variables using KNN imputation, where we filled missing values with the mean of the five closest neighbors.

- Model Selection: To identify the best-performing classification model, we utilized PyCaret to evaluate the performance of various classification algorithms. Among the models tested, Logistic Regression emerged as the top performer.

- Model Optimization with SMOTE: Recognizing the presence of class imbalance in the dataset, we employed the Synthetic Minority 

- Over-sampling Technique (SMOTE) to enhance the performance of our Logistic Regression model on the imbalanced dataset.

- Exploration of Neural Network Model: As part of our model exploration process, we experimented with a Neural Network model, which exhibited superior performance compared to traditional machine learning models.

- Neural Network Fine-Tuning: We further optimized the Neural Network architecture by adjusting parameters such as the number of dense layers, nodes, and dropouts. Through iterative fine-tuning, we achieved the best-weighted average performance of 89%.