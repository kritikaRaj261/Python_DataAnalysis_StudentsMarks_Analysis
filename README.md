# Student Marks Analysis

## Project Description
This project analyzes student marks in Math, Reading, and Writing subjects based on various factors including parent education, parental marital status, student exercise, and gender distribution. The analysis utilizes Python libraries such as NumPy, pandas, seaborn, and matplotlib to derive insights and visualize the data.

## Objectives
- **Analyze** student performance across Math, Reading, and Writing subjects.
- **Examine** how performance is influenced by parental education and marital status.
- **Assess** the impact of student exercise on academic performance.
- **Compare** performance between female and male students.
- **Identify** which subject students perform poorly in.

## Data Description
The dataset includes:
- `MathScore`: Scores in Math
- `ReadingScore`: Scores in Reading
- `WritingScore`: Scores in Writing
- `ParentEducation`: Education level of the parent
- `ParentMaritalStatus`: Marital status of the parent
- `StudentExercise`: Participation in extracurricular activities
- `Gender`: Gender of the student

## Analysis and Methods

### Data Preparation
```python
import pandas as pd

# Load the dataset
data = pd.read_csv('Expanded_data_with_more_features.csv')

# Data preprocessing steps
data = data.dropna()  # Example: Dropping missing values
