# Bank Churn Analysis & Prediction

## Project Overview
This project analyzes bank customer data to understand patterns of customer churn. 
It includes data exploration, cleaning, handling missing values, and training a predictive model to identify which customers are likely to churn.

## Structure
- **data/**: Contains the cleaned dataset used for analysis and model training.
- **notebooks/01_data_analysis.ipynb**: Data exploration, visualization, outlier detection, missing value handling, and preprocessing.
- **notebooks/02_model_training.ipynb**: Model training using Random Forest, evaluation (accuracy, F1-score, ROC-AUC), and prediction of churn.

## Steps Performed
1. **Data exploration**: histograms, boxplots, correlation analysis.
2. **Data preprocessing**: type conversions, handling missing values, outlier analysis.
3. **Predictive modeling**: Random Forest classifier to predict churn, evaluation using confusion matrix, classification report, and ROC-AUC.
4. **Advanced imputation**: Used Random Forest to fill missing values in 'type' column.


The project consists of **two Jupyter notebooks**:
1. `01_data_analysis.ipynb` – Exploratory Data Analysis (EDA), handling missing values, outliers, and managing data types.
2. `02_model_training.ipynb` – Encoding categorical variables, training a Random Forest model, evaluating predictions with accuracy, confusion matrix, classification report, and ROC-AUC.

## How to Run
0. pip install -r requirements.txt
1. Open the notebooks in the `notebooks/` folder using Jupyter Notebook or Jupyter Lab.
2. Ensure the `data/` folder is in the same parent directory as `notebooks/`.
3. Run `01_data_analysis.ipynb` to clean and prepare the dataset (`cleaned_data.csv` will be created).
4. Run `02_model_training.ipynb` to train the Random Forest model and evaluate results.


## Project Structure : 

Project/
│
├─ notebooks/
│   ├─ 01_data_analysis.ipynb       # Data exploration, EDA, cleaning
│   └─ 02_model_training.ipynb      # ML model training, evaluation
│
├─ data/
│   ├─ test_dataset_.parquet       # Original dataset
│   └─ cleaneddata.csv             # Dataset after preprocessing
│
├─ README.md                        # This file
├─ Requirements.txt                 # What you need to install 
