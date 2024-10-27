# End-to-End Machine Learning Pipeline for Student Placement Prediction

This repository contains an end-to-end machine learning pipeline developed to predict student placement outcomes based on CGPA and IQ scores. The project uses logistic regression for binary classification, taking students’ academic and cognitive metrics to forecast their placement success.

## Files

- **end-to-end-ml.ipynb**: The main Jupyter Notebook containing the entire pipeline, from data loading and preprocessing to model training and evaluation.
- **placement.csv**: The dataset used in this project, consisting of CGPA, IQ, and placement status.
- **model.pkl**: The trained logistic regression model, saved for making predictions on new data.

## Project Overview

1. **Data Loading and Exploration**: 
   - Loaded the data from `placement.csv`.
   - Dropped unnecessary columns and checked for null values.

2. **Preprocessing**:
   - Removed the `Unnamed: 0` column to clean the data for analysis.

3. **Exploratory Data Analysis (EDA)**:
   - Visualized the relationship between CGPA and IQ scores relative to placement status.

4. **Modeling**:
   - Chose logistic regression for binary classification.
   - Trained the model on the data to predict placement outcomes.

5. **Evaluation and Prediction**:
   - Evaluated model performance on test data.
   - Saved the model as `model.pkl` for future use.

## Setup and Usage

1. Clone this repository:
   ```bash
   git clone <https://github.com/red-devil002/end-to-end-ML-Project.git>


## Requirements

  1. Python 3.x
  2. Jupyter Notebook
  3. Libraries: numpy, pandas, matplotlib, sklearn (Logistic Regression)
     
## Dataset Details
`Columns:
  cgpa: CGPA of the student.
  iq: IQ score of the student.
  placement: Placement status (1 = placed, 0 = not placed).`
## License
This project is licensed under the MIT License.
