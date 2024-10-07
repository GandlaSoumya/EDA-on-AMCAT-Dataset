# Exploratory Data Analysis (EDA) Project: Salary Insights

## Project Overview

This project aims to explore a dataset of employee information to understand what factors affect salaries. The goal is to analyze various features, such as academic performance, job roles, and personal details, to see how they relate to salary. We'll also answer specific questions, such as whether gender influences specialization and whether certain job roles pay a specific salary range for fresh graduates.

## Objectives

1. **Data Understanding**: Learn about the different features (like academic grades, job roles, etc.) and how they might impact salary.
2. **Univariate Analysis**: Look at each feature on its own to understand patterns and detect any unusual data (outliers).
3. **Bivariate Analysis**: Explore relationships between pairs of features, such as how academic scores influence salary or how gender affects specialization.
4. **Research Questions**: Answer specific questions, such as checking salary claims and investigating if gender influences specialization choices.
5. **Conclusion**: Summarize the findings and provide key insights on what factors drive higher salaries.

## Dataset Description

The dataset contains various personal, academic, and professional details for each employee, such as:

- **ID**: Unique identifier for each person.
- **Salary**: The employee's salary (our target variable).
- **DOJ (Date of Joining)**: The date the employee started the job.
- **Designation**: The employee's job title (e.g., Software Engineer).
- **Gender**: Male or Female.
- **Academic Scores**: Scores from high school, college GPA, and test results in subjects like English, Logical reasoning, etc.
- **Specialization**: The employee’s college major (e.g., Computer Science).
- **Personality Traits**: Scores on personality aspects like conscientiousness, openness to experience, etc.

## Methodology

### 1. **Introduction and Data Summary**
   - Load and view the data to understand its structure.
   - Check for missing values and data types.

### 2. **Data Analysis**
   - Use **histograms** and **boxplots** to analyze the distribution of numerical features (like salary, GPA, test scores) and detect any outliers.
   - Use **count plots** to visualize the frequency of categorical features (like gender and job title).

### 3. **Exploring Relationships**
   - **Scatter plots** and **pair plots** to see how different numerical features (e.g., GPA and salary) relate to each other.
   - **Boxplots** and **swarm plots** to check how salary varies with categorical features (e.g., gender, specialization).
   - **Stacked bar plots** to visualize the relationship between two categorical variables (e.g., gender and specialization).

### 4. **Research Questions**
   - **Salary Claim**: We check if Computer Science graduates in certain job roles (like Software Engineer) actually earn between 2.5-3 lakhs as fresh graduates.
   - **Gender and Specialization**: We test if there's any significant relationship between gender and the choice of specialization.

### 5. **Conclusion**
   - Summarize the key findings, such as how different factors affect salary and any interesting patterns or trends discovered during the analysis.

### 6. **Bonus Analysis**
   - Explore additional insights, such as how personality traits might influence salary or if college reputation (tier) affects salary outcomes.

## Tools Used

- **Python**: For data analysis and visualization.
- **Pandas**: To handle and manipulate data.
- **Seaborn & Matplotlib**: To create charts and graphs.
- **SciPy**: To perform statistical tests.

## How to Run the Project

1. Clone the project from GitHub:
   ```
   git clone https://github.com/your-repo-name/EDA-salary-analysis.git
   ```
2. Install the required Python libraries:
   ```
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```
   jupyter notebook
   ```
4. Run the analysis in the notebook `EDA_Salary_Analysis.ipynb`.

## Conclusion

This project offers a deep dive into the dataset to uncover what drives salary differences, such as academic performance, job roles, and personal traits. It answers important questions like whether salary expectations match reality for fresh graduates and if gender plays a role in specialization choices.

