# Student Performance Analytics System

## Project Overview

The **Student Performance Analytics System** is a Python-based project developed to analyze student academic performance using **NumPy and Pandas**.

The system reads student data, processes marks and attendance, and generates useful performance information such as total marks, average marks, grades, pass/fail status, subject-wise performance, and top-performing students.

## Technologies Used

* Python
* NumPy
* Pandas
* Jupyter Notebook

## Dataset

The project uses a dataset containing **20 student records**.

The dataset includes:

* Student ID
* Student Name
* Department
* Python Marks
* AI Marks
* Mathematics Marks
* Attendance

The dataset is stored in `students.csv`.

## Features

The system performs the following operations:

1. Creates and reads the student dataset.
2. Stores the data in a Pandas DataFrame.
3. Calculates total marks for each student.
4. Calculates average marks.
5. Assigns grades based on average marks.
6. Determines pass/fail status.
7. Finds highest and lowest performance.
8. Calculates overall class average.
9. Performs subject-wise performance analysis.
10. Identifies top-performing students.
11. Performs attendance analysis.
12. Performs department-wise analysis.

## Grade Criteria

| Average Marks | Grade |
| ------------- | ----- |
| 90 and above  | A+    |
| 80–89         | A     |
| 70–79         | B     |
| 60–69         | C     |
| 50–59         | D     |
| Below 50      | F     |

## Pass/Fail Criteria

A student is considered **PASS** when the average marks are **40 or above**.

A student with an average below 40 is considered **FAIL**.

## Project Files

```text
Student-Performance-Analytics/
│
├── Student_Performance_Analytics.ipynb
├── students.csv
└── README.md
```

## How to Run

1. Open `Student_Performance_Analytics.ipynb` in Jupyter Notebook or VS Code.
2. Make sure `students.csv` is in the same project folder.
3. Run the notebook cells from top to bottom.
4. View the generated performance analysis and results.

## Expected Output

The system provides:

* Total and average marks
* Student grades
* Pass/fail statistics
* Highest and lowest performers
* Overall class average
* Subject-wise average performance
* Top 5 performing students
* Attendance analysis
* Department-wise performance

## Learning Outcomes

Through this project, the following concepts are demonstrated:

* Python variables and data types
* Conditional statements
* Loops
* Functions
* NumPy numerical calculations
* Pandas DataFrame operations
* Data analysis and processing
* Working with CSV datasets

## Repository

This project is maintained in a GitHub repository as part of the project submission.
