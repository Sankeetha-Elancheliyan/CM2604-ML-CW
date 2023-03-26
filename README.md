# CM2604-ML-CW
Email Spam Classification


This project is a study on the classification of emails into spam and non-spam categories based on their content in terms of words. The dataset used in this study was obtained from the UCI Machine Learning Repository. The study compares two machine learning models based on K Nearest Neighbors (KNN) and Decision Trees to identify the optimal model for email spam classification.

Code Structure

The code is organized into the following files:

ML_CW_KNN.ipynb: Jupyter notebook containing the code for KNN without PCA, with PCA and further enhancements.
DT_wo_PCA.ipynb: Jupyter notebook containing the code for Decision Trees without PCA.
ML_CW_Decision_Trees_PCA.ipynb: Jupyter notebook containing the code for Decision Trees with PCA.
DT_Further_Enhancement.ipynb: Jupyter notebook containing the code for Decision Trees and further enhancements.
README.md: documentation file.

Usage
To run the notebook, you can open it in Google Colaboratory.

Results

The study compares two machine learning models based on K Nearest Neighbors (KNN) and Decision Trees to identify the optimal model for email spam classification. In addition, feature reduction using Principal Component Analysis (PCA) was performed to reduce the dimensionality of the dataset and increase the accuracy of the models. The AdaBoost classifier with Decision Tree as the base estimator achieved an accuracy of an accuracy of 94%, precision of 96%, recall of 89%, and an F1-score of 92%, while the XGBoost classifier with PCA achieved an accuracy of 91%, precision of 90%, recall of 87%, and an F1-score of 89%. The XAdaBoost model with PCA showed the best performance.
