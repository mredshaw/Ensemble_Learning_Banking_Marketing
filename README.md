# Ensemble Learning in Action

## Project Overview
This project aims to build, evaluate, and compare ensemble models with standard machine learning models using the Term Marketing - Banking dataset. The goal is to demonstrate an understanding of each model's pros and cons and evaluate, from a business context, which model is most appropriate.

## Part 1: Data Preprocessing
- **Download the Dataset:** [Term Marketing - Banking Data](https://www.kaggle.com/datasets/prakharrathi25/banking-dataset-marketing-targets)
- **Tasks:**
  - Clean and explore the data. Summarize findings.
  - Build a pipeline to process the data (One Hot Encoding, Scaling, and other relevant transformations).
  - Explain the pre-processing approach and justify the transformations.

## Part 2: Build Baseline Models
- **Models:**
  - Logistic Regression
  - k-Nearest Neighbors (k-NN)
- **Tasks:**
  - Create baseline models and tune them.
  - Evaluate the models using appropriate performance metrics.

## Part 3: Ensemble Modelling
- **Models:**
  - Random Forest
  - AdaBoost
  - Bagging Classifier
  - Voting Classifier (with at least three different classification models)
- **Tasks:**
  - Build and tune each ensemble model.
  - Experiment with both hard and soft voting for the Voting Classifier.

## Part 4: Performance Comparison
- **Tasks:**
  - Compare the performance of all models (including baseline models).
  - Consider both the time required for the models to run and their performance on the dataset.

## Part 5: Interpretation and Justification
- **Tasks:**
  - Explain why the ensemble models performed the way they did.
  - Discuss the business implications.
  - Choose one model to implement in a business process and justify the choice.
  - Consider performance metrics, computational cost, and interpretability.

## Contents
- `Ensemble_Learning_Banking_Marketing.ipynb`: Jupyter Notebook containing the entire analysis, including data preprocessing, model development, evaluation, and summaries.
- `data/`: Folder containing the datasets used for analysis:
  - `train.csv`
  - `test.csv`

## Tools and Libraries Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## How to Run
1. Clone this repository: `git clone https://github.com/mredshaw/Ensemble_Learning_Banking_Marketing.git`
2. Open the Jupyter Notebook: `Ensemble_Learning_Banking_Marketing.ipynb`
3. Execute the cells in the notebook to see the analysis and results.

## Key Insights
The notebook provides detailed insights into the performance of various machine learning and ensemble models on the Term Marketing - Banking dataset. It also includes an evaluation of each model's business implications.
