# Drug Type Predictor

This notebook will create a model to predict drug to prescribe a patient given their demographic and other clinical data. 

The dataset is taken from [this Kaggle Dataset](https://www.kaggle.com/prathamtripathi/drug-classification)

## The Dataset

The dataset's target variable (drug type) contains 5 different medications: Drug A, Drug B, Drug C, Drug X and Y.

The feature sets of this dataset are Age, Sex, Blood Pressure, and Cholesterol of patients, and the target is the drug that each patient responded to.

## The Notebook
The notebook discusses various steps in the process:
* Pre-processing data by Label Encoding
* Exploring relationships between variables using boxplots and heatmaps
* Selection of appropriate models from various models using cross-validation
* Modeling via Decision Tree
* Evaluating with metrics: Jaccard Index, Precision, Recall, F1 Score, Accuracy
* Grid Search to select optimal hyperparam
* Final evaluation and conclusion