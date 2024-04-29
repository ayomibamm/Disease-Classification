<div id="header" align="center">
  <h1>
   Thyroid Disease Classification
</h1>
</div>

## Overview
The thyroid gland is crucial in regulating metabolic rate and growth through hormone synthesis. This project explores machine learning models to predict thyroid diseases, including hyperthyroidism, hypothyroidism, non-thyroidal illness syndrome (NTIS), and binding protein imbalance.

## Dataset
The dataset used in this project is [https://www.kaggle.com/datasets/yasserhessein/thyroid-disease-data-set].

## Methodology
- Data preprocessing: Exploratory data analysis, feature selection using Recursive Feature Elimination and Pearson Correlation, data scaling using RobustScaler.
- Model selection: Random Forest, XGBoost, Convolutional Neural Network.
- Evaluation: AUC comparison of the models, learning curve, and classification report.

## Results
The combined average classification reports for each classifier are as follows:

| Classifier              | Metric    | Score   |
|-------------------------|-----------|---------|
| RandomForestClassifier  | precision | 0.930705|
|                         | recall    | 0.938111|
|                         | f1-score  | 0.933865|
| XGBClassifier           | precision | 0.926281|
|                         | recall    | 0.925480|
|                         | f1-score  | 0.925706|
| CNNClassifier           | precision | 0.926649|
|                         | recall    | 0.921672|
|                         | f1-score  | 0.923710|

Further details and visualizations can be found in the project files.

## Instructions
1. Open the notebook file "Disease_Classification.ipynb" in Google Colab.
2. Run the notebook cells sequentially to execute the code.
3. Make sure to install any required libraries mentioned in the notebook.
4. Follow the instructions in the notebook for data loading, preprocessing, model training, and evaluation.
5. You can also download the notebook as a Python script and run it locally if preferred.

## Dependencies
- Python 3
- Libraries: scikit-learn, XGBoost, TensorFlow, etc.
