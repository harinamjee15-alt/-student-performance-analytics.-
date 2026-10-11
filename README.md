# Student Performance Analytics System

## 1. Project Overview

The Student Performance Analytics System is a Python-based data analysis project that analyzes student marks and attendance. It uses Python, Pandas, and NumPy to calculate student performance and generate meaningful results.

The project helps identify top-performing students, calculate average marks, assign grades, determine pass/fail status, and compare subject-wise performance.

## 2. Project Objectives

- Calculate total marks and average marks for each student.
- Assign grades based on a defined grading rule.
- Identify passing and failing students.
- Find the highest, lowest, and overall class average performance.
- Analyze subject-wise average marks.
- Identify the top three performing students.
- Save the analyzed results in a CSV file.

## 3. Technologies Used

- **Python** — Programming and data processing.
- **Pandas** — Data loading, DataFrame creation, and analysis.
- **NumPy** — Numerical calculations.
- **CSV** — Student data storage.
- **Visual Studio Code** — Development environment.
- **GitHub** — Project hosting and version control.

## 4. Dataset Description

The project uses a dataset containing 20 student records.

The dataset includes the following columns:

| Column | Description |
|---|---|
| Student_ID | Unique student identification number |
| Name | Student name |
| Department | Student department |
| Python | Python subject marks |
| Maths | Mathematics marks |
| DBMS | Database Management System marks |
| Attendance | Attendance percentage |

The original dataset is stored in `students.csv`.

## 5. Project Features

- Creates and loads student data using Pandas DataFrame.
- Uses NumPy for numerical calculations.
- Uses reusable functions and loops.
- Calculates total and average marks.
- Assigns grades based on average marks.
- Determines pass/fail results.
- Calculates highest, lowest, and class average performance.
- Generates subject-wise performance analysis.
- Identifies the top three students.
- Saves analyzed results to `student_analysis.csv`.

## 6. Project Structure

```text
student-performance-analytics/
│
├── main.py
├── students.csv
├── student_analysis.csv
├── README.md
└── Project_Documentation.docx
```

**Note:** Include `student_analysis.csv` after generating it by running the program. Update the filenames if your actual project structure is different.

## 7. Installation

Make sure Python is installed on your computer.

Install the required libraries by running this command in the VS Code terminal:

```bash
pip install pandas numpy
```

## 8. How to Run the Project

1. Download or clone the project repository.
2. Open the project folder in Visual Studio Code.
3. Open the terminal in the project folder.
4. Install the required libraries.
5. Run the following command:

```bash
python main.py
```

The program will display the student dataset, marks summary, grades, pass/fail results, subject-wise averages, and top-performing students.

It will also create `students.csv` and `student_analysis.csv` if the program includes the corresponding file-writing operations.

## 9. Grading and Pass/Fail Rules

The example grading rule is:

| Average Marks | Grade |
|---|---|
| 90–100 | A |
| 80–89 | B |
| 70–79 | C |
| 60–69 | D |
| Below 60 | F |

The example pass/fail rule is that a student passes only if they score at least 40 marks in every subject.

These are project-defined rules and can be changed if required.

## 10. Expected Output

The project displays:

- Total and average marks for each student.
- Grade and pass/fail status.
- Highest and lowest student averages.
- Overall class average.
- Subject-wise average marks.
- Top three performing students.

The actual output depends on the student dataset.

## 11. Learning Outcomes

Through this project, I practiced:

- Python variables, conditions, loops, and functions.
- Creating and manipulating Pandas DataFrames.
- Reading and writing CSV files.
- Numerical calculations using NumPy.
- Analyzing and interpreting student performance data.
- Organizing and publishing a Python project on GitHub.

## 12. Author

Name: HARINAM JEE

**Course:** Python with AI

**Department:** Computer Science and Engineering (CSE)

## 13. Conclusion

The Student Performance Analytics System demonstrates how Python, Pandas, and NumPy can be used to analyze student records and produce useful performance summaries. It reduces manual calculations and helps users understand student and class performance.
