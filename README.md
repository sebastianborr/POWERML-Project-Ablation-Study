# POWERML-Project-Ablation-Study
Results of the ablation study carried out for the final master's project (TFM): "Analysis and comparison of neural network architectures for energy consumption prediction" of the Master's Degree in Artificial Intelligence at the University of Alicante


This repository contains the results of the ablation study of various Machine Learning and Deep Learning architectures for the dataset from the study "Comparison of Machine Learning Algorithms for Power Consumption Prediction" (DOI: 10.1109/IRSEC.2018.8703007).

ML architectures studied: 
              - Linear Regression                - Ridge Regression
              - Lasso Regressio                  - Random Forest
              - Gradient Boosting                - XGBoost
              - Support Vector Regression (SVR)

DL architectures studied:
              - LSTM                - LSTM+CNN
              - CNN+LSTM            - BiLSTM
              - Transformers
              
The results for a first ablation study are included both in PDF format in the ./PDFOutput directory and in .csv forma0 in ./csvOutput.

In addition, the results of different executions of some of the models selected as the best and their comparison with the real results are included.
