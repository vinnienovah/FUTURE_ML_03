# FUTURE_ML_03

# Predict Student Scores

This project implements a **Simple Linear Regression Model** to predict student scores based on the number of hours they study. The project demonstrates end-to-end machine learning workflows, including data exploration, preprocessing, model building, and evaluation.

## Project Overview

The primary objective of this project is to explore the relationship between study hours and student scores and to build a regression model that accurately predicts a student's performance.

### Key Features
- **Input Feature**: `Hours` - Number of hours a student studies.
- **Target Variable**: `Scores` - The score a student achieves.

### Dataset
- The dataset contains 25 observations with two columns: `Hours` and `Scores`. 
- No missing values or duplicates were found during data cleaning.
- The dataset was used to train and evaluate the regression model.

## Workflow

1. **Data Exploration**:
   - Summary statistics and data types were analyzed.
   - Visualizations included boxplots, scatterplots, histograms, and Q-Q plots to understand the data distribution and relationships.

2. **Data Preprocessing**:
   - Checked for missing values and duplicates.
   - Verified the correlation between study hours and scores, confirming a strong positive relationship.

3. **Model Building**:
   - Split the data into training and testing sets (80% training, 20% testing).
   - Trained a **Simple Linear Regression Model** using Scikit-learn's `LinearRegression`.

4. **Evaluation**:
   - Evaluated the model using metrics such as:
     - **Mean Squared Error (MSE)**
     - **Root Mean Squared Error (RMSE)**
     - **Mean Absolute Error (MAE)**
     - **R² Score**

## Results

The model achieved the following performance on the test dataset:
- **Mean Squared Error (MSE)**: 18.94
- **Root Mean Squared Error (RMSE)**: 4.35
- **Mean Absolute Error (MAE)**: 3.92
- **R² Score**: 0.968  

An R² value of **0.968** indicates that the model explains 96.8% of the variability in the scores based on the hours studied, demonstrating an excellent fit.

## How to Run the Project

1. **Clone the repository**:
   ```bash
   git clone https://github.com/vinnienovah/FUTURE_ML_01
   cd FUTURE_ML_01
   
2. **Install the required libraries**:
   ```bash
   pip install -r requirements.txt
   
3. **Run the notebook**: Open and run the Jupyter notebook `Task_03_Predict_Student_Scores.ipynb` to:
- Explore the data.
- Train and evaluate the regression model.
- Visualize the results.

**Tools and Libraries Used**
- **Programming Language**: Python
- **Libraries**:
- - `pandas`, `numpy`: Data manipulation and analysis.
-- `matplotlib`, `seaborn`: Data visualization.
-- `scikit-learn`: Model building and evaluation.

**Key Learnings**
- How to implement a simple linear regression model.
- Importance of exploratory data analysis to understand the data.
- Evaluation of model performance using multiple metrics.

## Dataset
The datasets used in this project are provided by the [Kaggle: Students Score Dataset - Linear Regression](https://www.kaggle.com/datasets/shubham47/students-score-dataset-linear-regression).

  
**Author**
This project was completed as part of the Future Interns Machine Learning Internship. Feedback and suggestions are welcome!

Feel free to explore the code and reach out for collaboration. 🚀
  
