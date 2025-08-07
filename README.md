# elaktif-student-performance-analysis-Capstone


## Project Overview
This project is part of my Code:You Data Analysis Capstone. I used two real datasets about high school students in Math and Portuguese classes. My goal was to see what things might affect student grades like gender, school type, or where they live.
I look at two subjects: Math and Portuguese. I compare them to see if students do better in one subject than the other, and what things maybe help them get better grades.
I also compare students in both subjects to see where they do better, and if early grades (like grade 1 and 2) help predict the final grade.
This project is made in Python using Jupyter Notebook.


---
## Main Files:
There are three main parts in this project:
* student_math_clean.csv and student_portuguese_clean.csv: These are the cleaned datasets I used.
* student_analysis.ipynb: This is the notebook where I cleaned, explored, and analyzed the data.
* joined_student_data_with_avg.csv: This is the combined data after I joined both datasets and added new column.
## Datasets Used

### 1. Student Performance in Math

* **Source**:https://www.kaggle.com/datasets/dillonmyrick/high-school-student-performance-and-demographics?select=student_math_clean.csv
* **File**: `student-mat.csv`
* **Rows**: 395
* **Columns**: 33
* Includes things like age, gender, absences, family job, and grades.

### 2. Student Performance in Portuguese

* **Source**:https://www.kaggle.com/datasets/dillonmyrick/high-school-student-performance-and-demographics?select=student_portuguese_clean.csv
* **File**: `student-por.csv`
* **Rows**: 649
* **Columns**: 33
* Has similar structure as Math dataset.

---
## Features:
* Loading data:  I read CSV files using Pandas
* Cleaning: I fixed column names and made sure data types were correct
* New columns: I created average_grade 
* SQL: I put the data into SQLite database and did JOIN between tables
* Visualizations: I made 6 charts
* Functions: I made one function to calculate average of grades
* README: I made this file to explain my project

---
## Project Structure

* `data/`: Dataset files
* `notebooks/`: Jupyter notebooks
* `requirements.txt`: List of Python packages
* `README.md`: This file

---

## Objective

To understand how things like gender, school type, or where they live affect grades in Math and Portuguese classes. I also want to compare student results in both subjects.


---
## Technologies Used:
* Python: Main language for analysis
* Pandas: For working with tables and cleaning data
* Matplotlib: For making simple charts
* SQLite3: For making and joining database tables
* Jupyter Notebook:So 

 ## Data Summary
I used two real datasets about high school students in Math and Portuguese classes. My goal was to see what things might affect student grades like gender, school type, or where they live.
I split the data into two tables. One has student personal details like ID, name, and age.
The other has student grades for different tests.
This helps to organize the data better and makes it easier to work with.
I also compared the two subjects to see if students do better in one subject than the other.

I made this project using Python and Jupyter Notebook. I cleaned the data, joined it together, and made some visual charts to help me understand the results.
This helped me understand what factors might help students get better grades.
From the charts, I learned:

* Students who did well in Grade 1 often also did well in the Final.
* Students in different schools had different average grades.
* Female and male students had small differences in their average scores.
* Living in urban or rural areas may also affect average grades.
* This helped me understand what factors might help students get better grades.


---

## Data Sources

* [Student Performance – Math and Portuguese](https://archive.ics.uci.edu/ml/datasets/Student+Performance)
* [Another Source with Student Data](https://www.kaggle.com/datasets/dillonmyrick/high-school-student-performance-and-demographics)

## Final Notes
This project is done by me as a student still learning Python, data, and English. I did my best to clean the data, build charts, and explain what I see. Thank you for checking my work!
Big thanks to all my mentors for your help, support, and feedback. You helped me learn and improve a lot.

