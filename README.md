# Student Placement Predictor

## Project Description
The Student Placement Predictor is a machine learning project that predicts whether a student will be placed based on academic performance, skills, and preparation activities. The goal of this project is to analyze various student attributes and identify factors that influence placement outcomes.

## Dataset
The project uses the **Student Placement Prediction Dataset 2026** from Kaggle.

### Features Used
- Age
- Gender
- CGPA
- Branch
- College Tier
- Backlogs
- Study Hours per Day
- Internships Count
- Projects Count
- Certifications Count
- Coding Skill Score
- Aptitude Score
- Communication Skill Score
- Logical Reasoning Score
- Mock Interview Score
- Attendance Percentage
- Leadership Score

### Target Variable
- Placement Status

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## Methodology

### 1. Data Preprocessing
- Categorical variables such as Gender, Branch, and College Tier were encoded using **LabelEncoder**.
- The dataset was divided into **training (80%)** and **testing (20%)** sets using `train_test_split`.

### 2. Model Training
A **Linear Regression** model from `sklearn.linear_model` was used to train the model on the training dataset.

### 3. Model Evaluation
The model was evaluated using the following metrics:

- **Mean Squared Error (MSE)**
- **R² Score**

## Results

| Metric | Value |
|------|------|
| Mean Squared Error (MSE) | 0.0051 |
| R² Score | 0.9793 |

The high R² score indicates that the model performs well in predicting placement outcomes.

## Installation

Install the required libraries:

```bash
pip install pandas scikit-learn matplotlib seaborn kagglehub
```

## How to Run

1. Clone the repository
2. Open the project in **Jupyter Notebook or Google Colab**
3. Run the notebook to:
   - Load the dataset
   - Preprocess the data
   - Train the model
   - Evaluate the results

## Future Improvements
- Implement other machine learning models such as Random Forest and Gradient Boosting
- Perform feature engineering
- Improve model performance using hyperparameter tuning
