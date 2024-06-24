# Personal-Loan-Analysis

# Data Cleaning, Pickle File Saving, and Machine Learning Tasks

This repository contains code for cleaning and preprocessing a dataset, saving it to a pickle file, and performing machine learning tasks using Support Vector Machine (SVM) and Random Forest algorithms. The tasks are performed twice: first without feature selection and then with feature selection.

## Dataset
The dataset used in this project is personal-loan.

## Data Cleaning
The data cleaning process includes handling missing values, encoding categorical variables, and scaling numerical features. The cleaned dataset is saved to a pickle file for later use.

## Machine Learning Tasks
### Task 1: SVM and Random Forest without Feature Selection
In this task, both SVM and Random Forest classifiers are trained on the cleaned dataset without feature selection. The models are evaluated using cross-validation and the performance metrics are recorded.

### Task 2: SVM and Random Forest with Feature Selection
Feature selection is performed using SelectKBest. The selected features are then used to train SVM and Random Forest classifiers. The models' performance is evaluated and compared with the previous task to observe any improvement.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/your_repository.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter noteboosk or Python script to execute the tasks.
