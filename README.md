# Maintenance-Prediction-for-Turbofan-Jet-Engine

In this project, LSTM, RNN, and 1D-CNN models are developed for regression and classification tasks using time series data. 

Objectives:  
Regression objective: Predicting the remaining useful life (RUL) of a machine  
Classification objective: Predicting the failure of machine in upcoming specific periods

Dataset:
Data sets consists of multiple multivariate time series. Each data set is further divided into training and test subsets. Each time series is from a different engine i.e., the data can be considered to be from a fleet of engines of the same type.
The engine is operating normally at the start of each time series, and develops a fault at some point during the series. In the training set, the fault grows in magnitude until system failure. In the test set, the time series ends some time prior to system failure.
(Dataset link: https://www.kaggle.com/datasets/behrad3d/nasa-cmaps/data)
