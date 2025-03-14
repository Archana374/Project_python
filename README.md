# Project_python
Project Overview
This project analyzes the employee data of ABC Company, consisting of 458 rows and 9 columns, focusing on the distribution of employees across teams, their positions, salary expenditures, and the relationship between age and salary. The analysis aims to provide key insights into the company's workforce, identify trends, and highlight areas for improvement or focus.

Objectives:
Preprocessing: Clean the dataset by correcting data inconsistencies in the "height" column.
Team Distribution: Determine the distribution of employees across teams and calculate the percentage split.
Position Segregation: Classify employees based on their positions within the company.
Age Group Analysis: Identify the predominant age group among employees.
Salary Expenditure: Identify which team and position have the highest salary expenditure.
Correlation Analysis: Investigate the relationship between age and salary and visualize the correlation.
project structure
.
├── data/
│   └── employee_data.csv           # The dataset used for analysis
├── images/
│   ├── team_distribution.png       # Visualization for team distribution
│   ├── position_distribution.png   # Visualization for position distribution
│   ├── age_distribution.png        # Visualization for age distribution
│   ├── salary_expenditure_team.png # Visualization for salary expenditure by team
│   ├── salary_expenditure_position.png # Visualization for salary expenditure by position
│   └── age_salary_correlation.png  # Scatter plot for age vs salary correlation
├── analysis.py                     # Python script for data preprocessing and analysis
└── README.md                       # Project overview and instructions
