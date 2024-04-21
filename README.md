## Fuel Efficiency Price Prediction

This repository contains code and documentation for predicting fuel efficiency using regression tree models.

### Data Sources
- Features: [data.csv](https://raw.githubusercontent.com/EyalHadad/Files/main/data.csv)
- Labels: [labels.csv](https://raw.githubusercontent.com/EyalHadad/Files/main/labels.csv)

### EDA Visualization
Explore the data to identify meaningful features, correlations, and statistics. Visualize the correlation matrix and display descriptive statistics.

### EDA Insights
Gain insights from the visualization, such as strong positive correlations among certain features and weak correlations with model year.

### Preprocessing
Apply preprocessing techniques like handling missing values and splitting the dataset into training and testing sets while ensuring that data characteristics remain unchanged.

### Model Training and Evaluation
Train regression tree models on the training set and evaluate performance on the test set using Mean Squared Error (MSE) and R-squared (R2) metrics.

### Explainability
Use SHAP (SHapley Additive exPlanations) to explain feature contributions to the model. Explain specific predictions for three different cars.

## Classification Evaluation

Submit the classification evaluation question as a PDF file with ROC and precision-recall curves.

### ROC and Precision-Recall Curves

Calculate ROC and precision-recall curves with specified thresholds. Compare models and answer related questions.

### Curves Differences

Create a table with binary labels and predicted probabilities to draw ROC and precision-recall curves, explaining the chosen values.

## Ensemble

### AdaBoost Implementation

Implement AdaBoost algorithm from scratch and train it with different base estimators. Compare model performances and evaluate the effect of the number of learners.

## SVM

### Find the SVM Formula

Given points, find and draw the SVM hyperplane formula.

### Margin Size

Calculate the margin size based on the hyperplane.
