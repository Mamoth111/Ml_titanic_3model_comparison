# Titanic Machine Learning Model

## Overview
This project focuses on building a machine learning model to predict the survival of passengers aboard the Titanic based on various features such as age, gender, ticket class, etc.
## Dataset
The dataset used in this project is the famous Titanic dataset, which contains information about passengers including whether they survived or not. The datasets are available in the file.
## Files
- `train.csv`: The dataset containing information about passengers.
- `Titanic_project.ipynb`: Jupyter Notebook containing the code for data analysis, outlier analysis, exploratory data analysis (EDA), and building the machine learning model.
- `requirements.txt`: File containing the Python packages required to run the Jupyter Notebook.
## Data Analysis
- Exploratory data analysis (EDA) is performed to understand the structure and characteristics of the dataset.
- Outlier analysis is conducted to identify and handle outliers in the data.
  ## Machine Learning Model
- A machine learning model is built using all 3 boosting methods; ADA Boosting, Gradient Boosting and XGboosting.
- All 3 models are trained on a portion of the dataset and evaluated using appropriate metrics such as accuracy, precision, recall, and F1-score.
- Hyperparameter tuning is performed to optimize the model's performance.
## Results
- The performance of the machine learning model is assessed.
- The model's predictions are compared with actual survival outcomes to evaluate its effectiveness.
- Around %80 accuracy is achieved with all 3 boosting methods. Then comparison chart for different metrics are given at the end with conclusion.
- ## Usage
1. Clone the repository:

   ```bash
   git clone https://github.com/Mamoth111/titanic_3_model_comparison.git
