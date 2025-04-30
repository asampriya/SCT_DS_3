# Decision Tree Classifier with SMOTE and Grid Search
## Overview

Welcome to the repository for my third project at SkillCraft Technologies! This project involves building and evaluating a Decision Tree Classifier with SMOTE (Synthetic Minority Over-sampling Technique) and Grid Search for hyperparameter tuning. The aim is to improve the prediction of customer purchase behavior based on a bank marketing dataset.

## Project Description

### Data Source
The dataset used in this project is sourced from a bank marketing campaign. It contains various features such as customer age, job, marital status, education, and more. The target variable is whether the customer has subscribed to a term deposit.

### Steps and Methodology
1. *Data Exploration:* Initial analysis to understand the dataset's structure and identify key features.
2. *Data Cleaning and Encoding:* Handling missing values and encoding categorical variables.
3. *Data Balancing:* Applying SMOTE to address class imbalance in the target variable.
4. *Model Training:* Training a Decision Tree Classifier with optimized hyperparameters using Grid Search.
5. *Model Evaluation:* Evaluating model performance using metrics such as accuracy, precision, recall, and F1-score.
6. *Visualization:* Creating visualizations to communicate the findings effectively.

## Results

### Model Performance
- *Accuracy:* 0.84
- *Classification Report:* 
  - Precision: 0.94 (No Purchase), 0.40 (Purchase)
  - Recall: 0.88 (No Purchase), 0.57 (Purchase)
  - F1-Score: 0.91 (No Purchase), 0.47 (Purchase)
- *Confusion Matrix:* 
  - [[7001  951]
  - [ 467  624]]

### Testing with a Subset of the Dataset
- *Data Point 1:* Actual: No Purchase | Prediction: No Purchase
- *Data Point 2:* Actual: No Purchase | Prediction: No Purchase
- *Data Point 3:* Actual: No Purchase | Prediction: No Purchase
- *Data Point 4:* Actual: No Purchase | Prediction: Purchase
- *Data Point 5:* Actual: No Purchase | Prediction: No Purchase
- *Data Point 6:* Actual: No Purchase | Prediction: Purchase
- *Data Point 7:* Actual: No Purchase | Prediction: No Purchase
- *Data Point 8:* Actual: No Purchase | Prediction: No Purchase
- *Data Point 9:* Actual: No Purchase | Prediction: No Purchase
- *Data Point 10:* Actual: No Purchase | Prediction: No Purchase
- *Data Point 11:* Actual: Purchase | Prediction: No Purchase
- *Data Point 12:* Actual: No Purchase | Prediction: No Purchase
- *Data Point 13:* Actual: No Purchase | Prediction: No Purchase
- *Data Point 14:* Actual: Purchase | Prediction: No Purchase
- *Data Point 15:* Actual: No Purchase | Prediction: No Purchase
- *Data Point 16:* Actual: Purchase | Prediction: Purchase
- *Data Point 17:* Actual: No Purchase | Prediction: No Purchase
- *Data Point 18:* Actual: No Purchase | Prediction: No Purchase
- *Data Point 19:* Actual: No Purchase | Prediction: No Purchase
- *Data Point 20:* Actual: Purchase | Prediction: No Purchase

## Files in the Repository
- data/: Contains the dataset used for the project.
- notebooks/: Jupyter notebooks with code for data exploration, preprocessing, model training, and evaluation.
- README.md: This README file.

## How to Run the Project
1. Clone the repository:
   
   git clone https://github.com/yourusername/decision-tree-smote-project.git

2. Navigate to the project directory:
   
   cd decision-tree-smote-project

3. Install the required packages:
   ```
   pip install -r requirements.txt

4. Run the Jupyter notebooks to explore the data and train the model.


## Acknowledgements
I would like to thank SkillCraft Technologies for providing me with this exciting opportunity to work on this project and enhance my data science skills.
