# Titanic Dataset Analysis

## Objective
Analyze the Titanic passenger dataset using Python, NumPy, and Pandas to identify meaningful survival patterns.

## Project Structure
```text
titanic-analysis/
│
├── data/
│   └── titanic.csv
│
├── screenshots/
│
├── titanic_analysis.ipynb
└── README.md
```

## Tools Used
- Python
- NumPy
- Pandas
- Jupyter Notebook
- VS Code

## Analysis Performed
- Loaded the CSV dataset into a Pandas DataFrame
- Checked missing values and dataset structure
- Calculated descriptive statistics
- Filtered passengers by gender and class
- Sorted passengers by fare
- Grouped data to calculate survival rates
- Analyzed age groups, family size, and embarkation ports
- Calculated correlations between numeric variables

## Key Findings
1. The overall survival rate was approximately 38%.
2. Female passengers survived at a much higher rate than male passengers.
3. First-class passengers had a higher survival rate than third-class passengers.
4. First-class women had one of the highest survival rates.
5. Third-class men had one of the lowest survival rates.
6. Higher fares were associated with higher survival rates.
7. Children had relatively better survival outcomes than many adult groups.
8. Small families had better survival rates than passengers traveling alone or in very large families.
9. Passengers who embarked at Cherbourg had a higher survival rate than those from other ports.
10. Passenger class and fare showed meaningful relationships with survival.

## Dataset Source
[Titanic Dataset](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)