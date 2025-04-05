# Artificial-Intelligence-and-Big-Data-Capstone-
- This repository consist of my Capstone Project for AI nad Big Data which has a topic Loan Default Prediction Using Machine Learning

- This is the picture for running finally deployed model (XGBoost) https://phasegroup.streamlit.app/ which perfomed the best in terms of the accuracy 
- The project must be run in Python Language using either VS Code, Google Colaboratory and or Jupyter Notebook
-  This project uses machine learning to predict loan defaults based on an African dataset.

- The goal is to improve credit risk evaluation, reduce financial losses, and expand into new financial markets.

- The deployed model is available at https://phasegroup.streamlit.app/.

Setup Instructions
Environment Setup:

-Install Python (version 3.7 or higher).

- Required libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, and warnings.

- Use Google Colab or a local environment to run the code.

Dataset:

-Place the training (Train.csv) and testing (Test.csv) datasets in the working directory.

- Ensure correct paths for loading datasets in the code.

Steps to Run the Code
- Data Preprocessing:

Mount Google Drive (if using Colab).

- Load datasets (Train.csv and Test.csv) and inspect their structure.

Handle missing values using methods commented in the notebook.

Perform feature engineering:

- Encode categorical variables using one-hot encoding or label encoding.

- Log-transform skewed numerical features.

Exploratory Data Analysis (EDA):

- Visualize distributions of numerical features using histograms.

- Explore categorical variables with bar plots and pie charts.

- Analyze correlations between numerical features using heatmaps.

Model Training:

- Split data into training and validation sets using StratifiedKFold for handling imbalanced datasets.

-Train machine learning models (Logistic Regression, Random Forest and XGBoost).

- Evaluate models using metrics like F1-score, ROC-AUC, and confusion matrices.

Deployment:

- Deploy the trained model via Streamlit for real-world usage.
