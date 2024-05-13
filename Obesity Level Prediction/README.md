# Obesity Level Prediction

## Introduction
This project aims to predict the obesity level of individuals based on various features such as age, gender, height, weight, and lifestyle habits. The prediction task is treated as a classification problem, where the goal is to classify individuals into different obesity levels.

## Dataset
The dataset used in this project contains information about individuals' demographics, lifestyle habits, and obesity levels. It includes features such as age, gender, height, weight, frequency of physical activity, consumption of water and vegetables, family history of overweight, and mode of transportation. The target variable is the obesity level, which is categorized into several classes such as Normal Weight, Overweight Level I, Overweight Level II, Obesity Type I, Obesity Type II, and Obesity Type III.

## Data Preprocessing
- Categorical columns were label-encoded.
- Continuous columns were standardized using StandardScaler.

## Algorithms Used
Several classification algorithms were evaluated to predict the obesity level:
- Logistic Regression
- Decision Tree
- Random Forest (Best Performing)
- Gradient Boosting
- Support Vector Machine

## Evaluation
The Random Forest algorithm achieved the highest accuracy of 96.4%. It was selected as the best performing algorithm for this classification task.

## Files Included
- `ObesityDataSet_raw_and_data_sinthetic.csv`: The dataset used for training and testing.
- `Obesity Level Prediction.ipynb`: Jupyter Notebook containing the code for data preprocessing, model training, and evaluation.
- `README.md`: This file providing an overview of the project.

## Instructions
To run the project:
1. Clone the repository: `git clone https://github.com/your_username/obesity-level-prediction.git`
2. Navigate to the project directory: `cd obesity-level-prediction`
3. Open the `obesity_prediction.ipynb` notebook in Jupyter or any compatible environment.
4. Follow the instructions in the notebook to execute the code and reproduce the results.

## Dependencies
- Python 3
- pandas
- scikit-learn
- Jupyter Notebook (optional)



