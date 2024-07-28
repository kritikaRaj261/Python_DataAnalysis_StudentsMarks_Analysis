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
python
import pandas as pd

# Load the dataset
data = pd.read_csv('Expanded_data_with_more_features.csv')

# Data preprocessing steps
data = data.dropna()  # Example: Dropping missing value

# Insights from Analysis

Based on the analysis performed in the Jupyter Notebook `PROJECT_2_Student Marks Analysis.ipynb`, we have derived the following insights:

### 1. Gender Distribution
From the chart analyzing gender distribution:
- **Insight**: The number of female students is higher than the number of male students in the dataset.
  
 

### 2. Impact of Parental Education
From the chart evaluating the impact of parental education on student marks:
- **Insight**: Higher levels of parental education generally correlate with better student performance in Math, Reading, and Writing.

  ![Parental Education Impact Chart](C:\Users\krithika.raj\Downloads\Python Project New\Gender_Distribution.png)
  
  *Figure: Impact of Parental Education on Student Marks*

### 3. Marital Status of Parents
From the analysis of student performance based on the marital status of parents:
- **Insight**: The marital status of parents appears to have no significant impact on student marks.



### 4. Subject Performance
From the analysis of subject performance:
- **Insight**: Students generally perform poorly in Math compared to Reading and Writing.


## Conclusion
The analysis provides valuable insights into how various factors influence student performance. The key takeaways include the significant impact of parental education on student marks and the observation that students have relatively poorer performance in Math.




