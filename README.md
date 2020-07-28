# Predicting whether bank clients left

This repository contains a project that predicts whether the customer left the bank or not.

The prediction was performed with classification algorithms:
- Support Vector Machine (SVM);
- K-Nearest Neighbor (K-NN);
- Artificial Neural Network (ANN);
- Gradient Boosted Decision Trees (Xgboost).

Also, the database is unbalanced. Thus, I performed an over-sampling techniques to create synthetic examples using:
- Naive random over-sampling (RandomOverSampler);
- Synthetic Minority Oversampling Technique (SMOTE);
- Adaptive Synthetic (ADASYN).
